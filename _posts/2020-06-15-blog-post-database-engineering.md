---
layout: post
title: ReverseEngineering-DB-Covid19
description: The following discussion aims at Reverse Engineering a complex database regarding the trend of Coronavirus COVID-19 infection starting from the first cases in Italy (February 25, 2020, until May 3, 2020).
date: 2020-06-15
tags: GitHub-Projects
---

# 🔍🦠 ReverseEngineering-DB-Covid19

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

The following discussion aims at Reverse Engineering a complex database regarding the trend of Coronavirus COVID-19 infection starting from the first cases in Italy: February 25, 2020, until May 3, 2020. The deconstruction will be based on a master table, rewriting and reconstructing the database architecture with further analysis and development of the database through a more in-depth analysis, also eliminating additional redundancies through the normalization process. The development of the database will then be expanded to collect all the necessary data to determine the spread of the infection in provinces, regions, and worldwide.

N.B Data retrieved from [Dati COVID-19 Italia, Protezione Civile](https://github.com/pcm-dpc/COVID-19)

# ℹ️ Additional Information about DB-Covid19 Documentation

It has been thought to document and involve the use and creation of the database, supporting the reader with a guide to reading the data using a simple and basic language, not boring. In fact, we tried to follow the assigned track for the project's realization using and adding our ideas to make it a complete project, also enriching it with hyperlinks connected to the code for building the database created on DataGrip 20.1 connected to an DBMS ORACLE 18c Express Edition.

# 🛠️ DB_COVID19 Database Simulator

We have created a small database on Oracle Live, characterized by all the rules imposed on the discussion but with a restricted date index due to size issues (from March 19 to March 25), following the guidelines described in Chapter 5, Chapter 6, and 7. Thanks to Oracle Live Tutorial, it is possible to simulate the run of the defined DDLs and DMLs in this discussion.<br>
[Go to the Simulator](https://livesql.oracle.com/apex/livesql/file/tutorial_J6ZPO3GWTIOPQBJ48RHTTFJXB.html) <br> ![LiveSQL](https://www.oracle.com/technetwork/database/live-sql-logo-2715850.png)

# 📚 Project Created for Demonstration and Educational Purposes

The following discussion aims to develop a database project for the Database Basics exam at the University of Naples Federico II following adequate documentation.

# Created by
[Antonio Romano](https://github.com/LaErre9), [Giuseppe Riccio](https://github.com/giuseppericcio).
