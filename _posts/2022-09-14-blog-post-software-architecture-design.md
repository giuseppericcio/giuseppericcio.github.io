# 🦠 SelfTest COVID-19
[![Test di Unità](https://github.com/giuseppericcio/SelfTestCovid19/actions/workflows/Unit_Test.yml/badge.svg)](https://github.com/giuseppericcio/SelfTestCovid19/actions/workflows/Unit_Test.yml)
![Downloads](https://img.shields.io/github/downloads/giuseppericcio/SelfTestCovid19/total)
![GitHub](https://img.shields.io/github/license/giuseppericcio/SelfTestCovid19)

<div align="center">
  <img src="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/static/LogoOrizzontale.png?raw=true" width="588"/>
</div>

## 🚩 La Web Application 
Si desidera realizzare il sistema **SelfTest COVID-19** che sulla base dell’esito del test attiva la relativa prenotazione di un tampone in una delle farmacie più vicine al paziente, dunque un semplice servizio gestione prenotazioni tamponi nelle farmacie. 
Il SelfTest è un modello in grado di predire una certa probabilità di infezione al SARS-CoV-2(COVID-19) in base ai sintomi e/o alle malattie che il paziente manifesta e guidarlo a come comportarsi in caso di alta probabilità di infezione.
Ad esempio, se il sistema predice che il paziente X abbia una **probabilità di infezione tra il 75\% e il 100\%** allora verrà consigliato di recarsi in un centro di tamponi (farmacia, ecc. ) e di fare un **tampone molecolare**. Se il sistema predice che il paziente Y abbia una **probabilità di infezione tra il 50\% e il 75\%** allora verrà consigliato di fare un **tampone rapido** alla farmacia più vicina ad esso.

*🏁 Il sistema cerca di diminuire il numero di persone che si recano nelle farmacie per effettuare i tamponi al fine di evitare disservizi nelle stesse e per risparmiare sul costo dei tamponi da parte dei pazienti. In che modo? Prevedendo la probabilità potenziale al COVID-19 e in base al valore ottenuto può effettuare o meno una prenotazione del tampone alla farmacia più vicina.*

## 📋 La Documentazione
E' possibile consultare la completa documentazione al seguente link <a title="Link al documento" href="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/Progetto%20SAD%20-%20Antonio%20Romano%20M63001315%20-%20Giuseppe%20Riccio%20M63001314.pdf">
🔗 documento </a>
- Introduzione
- Avvio della progettazione
- Processo di sviluppo
- Analisi dei requisiti
- Architettura e progettazione del software
- Implementazione del software
- Testing
- Rilascio del software
- Uso del prodotto software

## 🔧 Tools utilizzati
|                       **FRONT END**                       |  **TOOLS**                  |
|:---------------------------------------------------------:|--------------------|
| _FRAMEWORK_                                               | BOOTSTRAP          |
| _LANGUAGE_                                                | HTML, CSS, JS      |
|                        **BACK END**                       |                    |
| _FRAMEWORK_                                               | FLASK              |
| _LANGUAGE_                                                | PYTHON             |
| _TESTING_                                                 | PYTEST, LOCUST, GTMETRIX  |
| _DATABASE_                                                | SQLITE             |
| **TOOLS PER IL SUPPORTO ALLA REALIZZAZIONE DEL SOFTWARE** |                    |
| _CODE_                                                    | VISUAL STUDIO CODE |
| _UML DESIGN_                                              | VISUAL PARADIGM    |
| _SCRUM SUPPORT_                                           | JIRA               |
| _WEB HOSTING_                                             | PYTHONANYWHERE     |

## 📈 System Context Diagram
Il diagramma seguente mostra ad alto livello come gli attori esterni (il paziente, il paziente registrato, la farmacia e l'admin di sistema) interagiscono con il sistema. In particolare, all'accesso del sistema, al *paziente* viene mostrato il form del *Modello di ML* per la predizione al COVID19, esso inserirà i sintomi e malattie che esso manifesta e il sistema restituirà l'esito. 
Se l'**esito del test** è compreso tra il 50\% e il 75\% verrà indirizzato in maniera automatica al sistema di prenotazione di un tampone rapido alla farmacia più vicina. Se l'esito è maggiore del 75\% allora verrà indirizzato in maniera automatica al sistema di prenotazione di un tampone molecolare alla farmacia più vicina. Effettuando la prenotazione, il paziente si registra al sistema, se già non lo è, diventando così un *paziente registrato*. La *farmacia* aggiornerà la disponibilità dei tamponi rapidi/molecolari e aggiungerà l'esito del tampone effettuato al paziente. 
L'*admin di sistema* aggiornerà la lista delle farmacie aderenti al sistema. Inoltre aggiornerà il modello di ML per migliorare l'accuratezza dei risultati.

<div align="center">
  <img src="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/Immagini%20e%20Diagrammi/Diagrammi%20UML/System%20Context%20Diagram%20SelfTestCOVID19.png?raw=true" width="788"/>
</div>

## ✏️ Come funziona il test
<div align="center">
<center><img src="https://selftestcovid19.pythonanywhere.com/static/SchemeTestFunction.jpg" width="788"/></center>
</div>

## 📽️ Video Demo della Web Application
Si mostrano tutte le funzionalità implementate nella web application, dallo svolgimento del test fino alla gestione delle farmacie aderenti al sistema.

<iframe width="560" height="315" src="https://user-images.githubusercontent.com/64225083/188891848-4e4ad96a-c5f2-485f-b708-99068c5bee3d.mp4" frameborder="0" allowfullscreen></iframe>

⚠️ **ATTENZIONE** L’applicazione realizzata è solo a scopo dimostrativo, pertanto la probabilità calcolata può risultare incerta giacché, come già detto in precedenza, il dataset è datato e non aggiornato e i sintomi del virus mutano e variano ogni giorno. I sintomi, malattie e informazioni relative al COVID19 inserite nel selftest non verranno memorizzate. 

## ✔️ La Web App è disponibile, basta un browser! 
Al seguente link si può provare la web application <a title="Link al sito" href="https://selftestcovid19.pythonanywhere.com">
🔗 WebApp </a>

**Credenziali di accesso**

😎 ADMIN: *username* **admin** *password* **admin** 

😀 FARMACIA: *username* **donbosco@farmacia.it** *password* **prova1** (*puoi cambiare farmacia entrando dall'ADMIN*)

# Gli Autori
- <a title="Antonio Romano" href="https://github.com/LaErre9" target="_blank" > Antonio Romano </a>
- <a title="Giuseppe Riccio" href="https://github.com/giuseppericcio" target="_blank" > Giuseppe Riccio </a>

# Progetto realizzato per soli scopi dimostrativi ed educativi
La seguente trattazione è mirata alla realizzazione di un progetto software per l'esame di Software Architecture Design (A.A 2021/2022) all'**Università degli Studi di Napoli Federico II**.
