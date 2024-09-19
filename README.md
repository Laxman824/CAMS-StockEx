# Simplified Stock Exchange Platform

## Overview

The Simplified Stock Exchange Platform is a web application that demonstrates the capabilities of Java and Spring Boot, along with frontend technologies. It simulates a basic stock exchange environment, allowing users to manage stocks, perform trading operations, and generate reports.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Importing the Project](#importing-the-project)
- [Running the Project](#running-the-project)
- [Accessing the Application](#accessing-the-application)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Development Environment](#development-environment)

## Prerequisites

- Java JDK 8 or higher
- Maven
- Spring Tools Suite (STS) (recommended IDE)
- H2 Database (included)

## Installation

### Windows

1. Install JDK from [Oracle's website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
2. Set the `JAVA_HOME` environment variable
3. Install Maven from [Maven's website](https://maven.apache.org/download.cgi)
4. Install Spring Tools Suite from [Spring's website](https://spring.io/tools)

### Ubuntu

1. Install Java:
   ```bash
   sudo apt update
   sudo apt install openjdk-11-jdk
   ```
2. Install Maven:
   ```bash
   sudo apt install maven
   ```
3. Install Spring Tools Suite (download .tar.gz file from the official website and extract)

## Importing the Project

1. Open Spring Tools Suite
2. Go to `File > Import`
3. Select `Existing Maven Projects`
4. Browse to the project directory and select it
5. Click `Finish`

## Running the Project

1. In STS, select the project
2. Right-click and select `Run As > Maven clean`
3. Run `Maven build` with goal `clean install`
4. Select `Run As > Run Configurations`
5. Choose a Maven Build configuration and click `Run`
6. Run `StockexchangeApplication.java` in `src/main/java`

## Accessing the Application

- Main page: http://localhost:8080/
- H2 console: http://localhost:8080/h2-console/

## Features

### User Management
- Registration and login
- Profile management
- Role-based access control (Investor and Admin roles)

### Stock Management
- Create and manage stocks (Admin)
- File upload for company listings
- Display stock information

### Trading
- Buy/sell stocks
- Order settlement
- Order history
- Portfolio management

## Technology Stack

- Backend: Java, Spring Boot
- Database: H2 (in-memory)
- Frontend: (Not specified in the original content)

## Development Environment

- IDE: Spring Tools Suite
- Build Tool: Maven
- Version Control: (Not specified, but Git is recommended)

For more detailed information on functional requirements, non-functional requirements, and assessment criteria, please refer to the project documentation.
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/10.png" width="500" alt="Screenshot 1" />
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/11.png" width="500" alt="Screenshot 1" />
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/12.png" width="500" alt="Screenshot 1" />
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/13.png" width="500" alt="Screenshot 1" />
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/14.png" width="500" alt="Screenshot 1" />
<img src="https://github.com/Laxman824/CAMS-StockEx/blob/main/screenshots/15.png" width="500" alt="Screenshot 1" />
