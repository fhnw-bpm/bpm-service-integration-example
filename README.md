# BPM Service Integration Example

[![License](https://img.shields.io/:license-apache-blue.svg)](https//www.apache.org/licenses/LICENSE-2.0.html)
[![Deploy to Heroku](https://img.shields.io/badge/deploy%20to-Heroku-6762a6.svg?longCache=true)](https://heroku.com/deploy)

This example project can be used to create a fresh Camunda-based workflow including variables and form fields.

- [1. BPM Workflow Example Project](#1-bpm-workflow-example-project)
- [2. Modelling the Workflow](#2-modelling-the-workflow)
    - [Workflow Modelling](#workflow-modelling)
    - [Model Storage](#model-storage)
- [3. Testing](#3-testing)
    - [Troubleshooting](#troubleshooting)
- [4. Configuration of Users and Groups](#4-configuration-of-users-and-groups)
    - [Enable Authorisation](#enable-authorisation)
    - [Define Users and Groups](#define-users-and-groups)
    - [Define Authorisations](#define-authorisations)
- [Prerequisites](#prerequisites)
    - [Download Java Development Kit 8 (1.8.0)](#download-java-development-kit-8-180)
    - [Configure JDK in Eclipse](#configure-jdk-in-eclipse)
- [Maintainer](#maintainer)
- [License](#license)

## 1. BPM Service Integration Example Project

Download this repository and extract the files.

This repository is a copy of the [digibp-camunda-template repository on GitHub](https://github.com/DigiBP/digibp-camunda-template) and is based on the following structure:

![](https://digibp.github.io/images/wiki/digibp-camunda-template-stucture.png)

## Prerequisites

The Java Development Kit 8 (1.8.0) must be installed on your machine to run the provided projects containing:
- Camunda Workflow Engine
- Spring Boot

> Note: Currently only JDK version 8 (1.8.0) is supported

### Download Java Development Kit 8 (1.8.0)

If JDK 8 (1.8.0) is not installed on your local machine, then you can download it from [http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). Download and install JDK 8 (1.8.0) for your operating system.

![](https://digibp.github.io/images/wiki/JDK%20Download.png)

### Configure JDK in Eclipse

You may have to update your installed JRE to JDK in Eclipse:

![](images/2018-03-26_13h11.gif) 

## Maintainer
- [Andreas Martin](https://github.com/andreasmartin)
- [Digitalisation of Business Processes](https://github.com/digibp)

## License

- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)