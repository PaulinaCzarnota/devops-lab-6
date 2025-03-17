This repository contains my Lab 6 - Docker and Containers solution for the Introduction to DevOps module in the third year of the Computer Science course at TU Dublin.

# Overview

This lab explores Docker and containerization by building a Docker image for a Flask web application, running it in a container, and analyzing the `python:3.13` Dockerfile. The goal is to understand Dockerfiles, manage containers, analyze image layers, and investigate the process of building Python from source.

# Key Tasks

- Created a `Dockerfile` to containerize a Flask app.
- Built and ran the Docker container, mapping ports for accessibility.
- Verified container operation and tested the web application.
- Inspected the `python:3.13` image, traced its base (`buildpack-deps:bookworm`), and analyzed its layered structure.
- Examined why Python is built from source instead of installed via `apt`, identifying `make` commands used in the compilation process.
- Stopped and removed the container and image after testing.

This lab provided hands-on experience with Docker, demonstrating containerization, deployment, and image inspection techniques essential for DevOps and modern application development.
