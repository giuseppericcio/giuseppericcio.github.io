# giuseppericcio.github.io

Personal academic website, built with Jekyll and served by GitHub Pages.

## How content is organised

| File | What | Edited by |
| --- | --- | --- |
| `_data/profile.yml` | name, roles, bio, links | hand |
| `_data/news.yml` | news feed | hand (+ auto entry for each new paper) |
| `_data/experience.yml`, `_data/awards.yml` | experience, education, awards | hand |
| `_data/curation.yml` | selected papers, extra links, featured/hidden repos | hand |
| `_data/publications.yml` | publications | **generated** |
| `_data/repos.yml` | GitHub projects | **generated** |
| `_data/scholar.yml`, `_data/sync.yml` | citation metrics, last sync date | **generated** |
| `_posts/` | blog posts | hand |

## Automatic updates

`.github/workflows/site.yml` runs `scripts/update_data.py` every Monday (and on demand from
the Actions tab), commits any change under `_data/`, then builds and deploys the site.

The script:

1. reads the publication list and metrics from the Google Scholar profile page
   (if Scholar cannot be reached, the current list is kept);
2. collects my GitHub repos plus the [PRAISELab-PicusLab](https://github.com/PRAISELab-PicusLab)
   repos I contributed to, and links each paper to its code / Hugging Face demo or dataset;
3. applies `_data/curation.yml` and adds a news entry for each new paper.

Run it locally with:

```sh
pip install -r requirements.txt
python scripts/update_data.py                            # full refresh
python scripts/update_data.py --no-scholar --no-github   # only re-apply curation
```

## One-time setup

**Settings → Pages → Build and deployment → Source: GitHub Actions.**
