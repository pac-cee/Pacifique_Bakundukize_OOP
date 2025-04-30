# OOP Java Project Suite

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/<your-github-username>/<repo-name>/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---
## Author & Credits

**Pacifique Bakundukize**  
**Student ID: 26798**

## 📦 Project Overview

A collection of advanced Java OOP projects for inventory, shopping, and insurance management. Each project is fully containerized with Docker for easy deployment and testing.

**Projects included:**
- **StockManagement**: Manage warehouse inventory, suppliers, and stock items interactively.
- **OnlineShoppingSystem**: Simulate an e-commerce experience with cart, checkout, and multiple product categories.
- **InsuranceSystem**: Manage vehicle insurance policies, file claims, and generate reports.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Quick Start (Clone, Build, Run)](#-quick-start-clone-build-and-run-each-project)
- [Run from Docker Hub](#how-to-pull-and-run-my-projects-from-docker-hub)
- [Direct Docker Hub Links](#direct-docker-hub-links)
- [Author & Credits](#author--credits)

---

## 🛠️ Quick Start: Clone, Build, and Run Each Project

### 1. Clone the Repository
```sh
git clone https://github.com/pac-cee/Pacifique_Bakundukize_OOP.git
cd Pacifique_Bakundukize_OOP
```

### 2. Build a Project's Docker Image
Replace `<ProjectDir>` and `<image-name>` as needed:
```sh
cd <ProjectDir>
docker build -t <image-name> .
```
Examples:
- StockManagement: `cd StockManagement && docker build -t stock-management .`
- OnlineShoppingSystem: `cd OnlineShoppingSystem && docker build -t online-shopping-system .`
- InsuranceSystem: `cd InsuranceSystem && docker build -t insurance-system .`

### 3. Run the Project's Docker Container
```sh
docker run --rm -it <image-name>
```
Examples:
- `docker run --rm -it stock-management`
- `docker run --rm -it online-shopping-system`
- `docker run --rm -it insurance-system`

---

## How to Pull and Run My Projects from Docker Hub

You can easily run any of my Java projects using Docker. Just follow these steps:

### 1. Pull the Image
Choose the project you want and run the corresponding command:

- **Stock Management**
  ```sh
  docker pull paccee/stock-management-26798
  ```
- **Online Shopping System**
  ```sh
  docker pull paccee/online-shopping-system-26798
  ```
- **Insurance System**
  ```sh
  docker pull paccee/insurance-system-26798
  ```

### 2. Run the Project
After pulling, run the project with:

- **Stock Management**
  ```sh
  docker run --rm -it paccee/stock-management-26798
  ```
- **Online Shopping System**
  ```sh
  docker run --rm -it paccee/online-shopping-system-26798
  ```
- **Insurance System**
  ```sh
  docker run --rm -it paccee/insurance-system-26798
  ```

---

## Direct Docker Hub Links
- [Stock Management](https://hub.docker.com/r/paccee/stock-management-26798)
- [Online Shopping System](https://hub.docker.com/r/paccee/online-shopping-system-26798)
- [Insurance System](https://hub.docker.com/r/paccee/insurance-system-26798)

---
---

**Simply copy and paste the commands above in your terminal to run any project instantly!**
