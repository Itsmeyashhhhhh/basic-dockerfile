# Basic Dockerfile Project

This repository contains a simple, lightweight Docker configuration built as part of the [roadmap.sh Basic Dockerfile](https://roadmap.sh/projects/basic-dockerfile) challenge. 

**Project URL:** https://roadmap.sh/projects/basic-dockerfile

The goal of this project is to build a minimal Docker image using Alpine Linux that prints a welcoming message to the console upon execution.

---

## Prerequisites

Before running this project, ensure you have the following installed on your machine:
* **Docker Engine** (or an alternative runtime environment like WSL2 with Docker installed)

---

## How to Build and Run

Follow these simple steps in your terminal to build and run the container:

### 1. Build the Docker Image
Navigate to the project's root directory and compile the Dockerfile into an image tagged `hello-captain`:
```bash
docker build -t hello-captain .