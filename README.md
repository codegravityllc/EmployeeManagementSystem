# Getting Started with Docker on Windows

This guide will help you install Docker Desktop on your Windows machine and run your application using Docker containers.

## What is Docker?

Docker is a platform that lets you package applications and their dependencies into containers. This ensures your app runs the same everywhere — no more "it works on my machine" issues!

## Install Docker Desktop on Windows

### Prerequisites
- **Windows 10/11 Pro, Enterprise, or Education**
- **WSL2** (Windows Subsystem for Linux 2) recommended

> If you're on Windows Home, you can still use Docker with WSL2.

### Steps to Install

1. **Download Docker Desktop**

   [Download from official site](https://www.docker.com/products/docker-desktop/)

2. **Run the installer**
    - Follow the instructions
    - Enable **WSL2** when prompted (recommended)

3. **Restart your PC** after installation

4. **Verify installation**

   Open Command Prompt or PowerShell and run:
   ```bash
   docker --version
   docker compose version
   
#### (How to run it)

1.Start your application
docker compose up

2.Stop your application
docker compose down

3.Rebuild containers (if needed)
docker compose up --build
