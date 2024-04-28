---
layout: post
title: SelfTest COVID-19
description: The aim is to create the SelfTest COVID-19 system which, based on the test result, activates the related booking for a swab at one of the pharmacies closest to the patient, thus a simple service for managing swab bookings in pharmacies.
date: 2022-09-14
tags: GitHub-Projects
---

# 🦠 SelfTest COVID-19

![Downloads](https://img.shields.io/github/downloads/giuseppericcio/SelfTestCovid19/total?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/giuseppericcio/SelfTestCovid19?style=for-the-badge)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

<div align="center">
  <img src="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/static/LogoOrizzontale.png?raw=true" width="588"/>
</div>

## 🚩 The Web Application 
The **SelfTest COVID-19** system is aimed at activating the relative booking of a swab at one of the pharmacies closest to the patient based on the test result, thus a simple service for managing swab bookings in pharmacies.
The SelfTest is a model capable of predicting a certain probability of SARS-CoV-2 (COVID-19) infection based on the symptoms and/or diseases the patient manifests and guiding them on how to behave in case of a high probability of infection.
For example, if the system predicts that patient X has a **probability of infection between 75% and 100%**, they will be advised to go to a testing center (pharmacy, etc.) and take a **molecular swab**. If the system predicts that patient Y has a **probability of infection between 50% and 75%**, they will be advised to take a **rapid swab** at the nearest pharmacy.

*🏁 The system aims to reduce the number of people going to pharmacies to perform swabs in order to avoid service disruptions and to save on the cost of swabs for patients. How? By predicting the potential probability of COVID-19 and based on the obtained value, it can make a swab booking at the nearest pharmacy or not.*

## 📋 Documentation
The complete documentation can be found at the following <a title="Link to the document" href="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/Progetto%20SAD%20-%20Antonio%20Romano%20M63001315%20-%20Giuseppe%20Riccio%20M63001314.pdf">
🔗 link </a>
- Introduction
- Design Start
- Development Process
- Requirements Analysis
- Software Architecture and Design
- Software Implementation
- Testing
- Software Release
- Use of the Software Product

## 🔧 Tools Used

| **FRONT END**                                             | **TOOLS**                 |
|-----------------------------------------------------------|---------------------------|
| _FRAMEWORK_                                               | BOOTSTRAP                 |
| _LANGUAGE_                                                | HTML, CSS, JS             |
|                        **BACK END**                       |                           |
| _FRAMEWORK_                                               | FLASK                     |
| _LANGUAGE_                                                | PYTHON                    |
| _TESTING_                                                 | PYTEST, LOCUST, GTMETRIX  |
| _DATABASE_                                                | SQLITE                    |
| **TOOLS FOR SOFTWARE DEVELOPMENT SUPPORT**                |                           |
| _CODE_                                                    | VISUAL STUDIO CODE        |
| _UML DESIGN_                                              | VISUAL PARADIGM           |
| _SCRUM SUPPORT_                                           | JIRA                      |
| _WEB HOSTING_                                             | PYTHONANYWHERE            |

## 📈 System Context Diagram
The following diagram shows at a high level how external actors (the patient, the registered patient, the pharmacy, and the system admin) interact with the system. In particular, upon accessing the system, the *patient* is shown the *ML Model* form for predicting COVID19, where they will enter the symptoms and diseases they manifest, and the system will return the result.
If the **test result** is between 50% and 75%, the patient will be automatically directed to the rapid swab booking system at the nearest pharmacy. If the result is greater than 75%, the patient will be automatically directed to the molecular swab booking system at the nearest pharmacy. By making the booking, the patient registers with the system, if they are not already registered, thus becoming a *registered patient*. The *pharmacy* will update the availability of rapid/molecular swabs and add the result of the swab performed on the patient. 
The *system admin* will update the list of pharmacies participating in the system. Additionally, they will update the ML model to improve result accuracy.

<div align="center">
  <img src="https://github.com/giuseppericcio/SelfTestCovid19/blob/main/Immagini%20e%20Diagrammi/Diagrammi%20UML/System%20Context%20Diagram%20SelfTestCOVID19.png?raw=true" width="788"/>
</div>

## ✏️ How the Test Works
<div align="center">
<center><img src="https://selftestcovid19.pythonanywhere.com/static/SchemeTestFunction.jpg" width="788"/></center>
</div>

## 📽️ Video Demo of the Web Application
The video demonstrates all the functionalities implemented in the web application, from performing the test to managing pharmacies participating in the system.

<iframe width="100%" height="100%" src="https://user-images.githubusercontent.com/64225083/188891848-4e4ad96a-c5f2-485f-b708-99068c5bee3d.mp4" frameborder="0" allowfullscreen></iframe>

⚠️ **ATTENTION** The application developed is for demonstration purposes only, therefore the calculated probability may be uncertain since, as previously mentioned, the dataset is dated and not updated, and the symptoms of the virus change and vary every day. The symptoms, diseases, and information related to COVID19 entered in the self-test will not be stored.

## ✔️ The Web App is available, just a browser away!
You can try the web application at the following link <a title="Link to the website" href="https://selftestcovid19.pythonanywhere.com">
🔗 WebApp </a>

**Access Credentials**

😎 ADMIN: *username* **admin** *password* **admin** 

😀 PHARMACY: *username* **donbosco@farmacia.it** *password* **prova1** (*you can change the pharmacy by logging in as ADMIN*)

# The Authors
- [Antonio Romano](https://github.com/LaErre9)
- [Giuseppe Riccio](https://github.com/giuseppericcio)

# Project created for demonstration and educational purposes
This document aims to develop a software project for the Software Architecture Design exam (A.Y. 2021/2022) at the **University of Naples Federico II**.
