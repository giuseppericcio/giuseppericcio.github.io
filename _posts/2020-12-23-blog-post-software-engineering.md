---
layout: post
title: Call Center Software System
description: This document aims at the development cycle of a software system dedicated to managing a call center.
date: 2020-12-23
tags: GitHub-Projects
---

# ☎️ Call Center Software System

[![Licence](https://img.shields.io/github/license/giuseppericcio/CallCenterManagementSystem_prototipo?style=for-the-badge)](./LICENSE)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

This document focuses on the development cycle of a software system dedicated to those who manage or intend to start managing: a call center, telemarketing activity, appointment booking, telephone operators, or in-house activity within their own company. It will analyze the tools and systems that will enable maximum efficiency, both in the number of calls made and completed sales. **The discussion will focus on the functions and definitions that can facilitate the daily work of administrators, system administrators, switchboard operators, sales agents, and their interaction.**

# 💡 Our Idea
The name of our call center management software system is IOCaller Software System (aiokôlər), where IO stands for "**Inbound and Outbound**", indicating the two classifications of switchboard operators. Below is a proposed logo for the software system in question.

<p align="center">
  <img src="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/GestioneCallCenter/images/logo.png?raw=true">
</p>

# 📄 Full Document (Software Development Cycle)
The documentation can be found at the following <a href="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/Documento_IS.pdf">link</a><br>
The document is divided into sections:
- *Introduction*
- *Data Specification Documentation*
- *Analysis Documentation*
- *Design Documentation*
- *Implementation Document*
- *Software Implementation*
- *Testing Document*

<hr>

### Project Overview
# Solution to the Problem (Complete Package Class Diagram)

The realization of the Complete Package Diagram was obtained starting from the identification in the design sequences of the following classes:
- *ConsoleBoundary Class*
- *Controller and ControllerImpl Classes*
- *Entity Class*
- *DAO (Database Interaction) Class*

<p align="center">
  <img src="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/Diagrammi/Class%20Diagram.png?raw=true">
</p>


# From Class Diagram Package to Software Implementation
We show the hierarchy of the implemented Software interfaces, (we obviously invite the reader that this graph is the result of a complete implementation present in the repository)
<p align="center">
  <img src="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/Diagrammi/GerachiaInterfaccia.JPG?raw=true">
</p>


# Try Running Our Sample Program
You can try running the program by following these steps
- <a href="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/IOCaller.jar">Download the .jar file</a> 
- <a href="https://github.com/iocaller/CallCenterManagementSystem_prototipo/blob/main/Database">Download the database</a>

## 🔧 Prerequisites
- Java Virtual Machine
- Installation of <a href="https://www.apachefriends.org/it/download.html">MySQL</a> on the terminal and installation of the provided database

# Authors (Team - 9, Software Engineering Project)
- [Antonio Romano](https://github.com/LaErre9/)
- [Giuseppe Riccio](https://github.com/giuseppericcio/)
- Salvatore Pernice
- Giovanni Scognamiglio

# Project Created for Demonstration and Educational Purposes
This document aims to develop a software project for the **University of Naples Federico II** Software Engineering exam following appropriate documentation.
