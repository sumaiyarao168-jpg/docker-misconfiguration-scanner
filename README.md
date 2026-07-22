# docker-misconfiguration-scanner


---

# **Day 19 – Docker Container Misconfiguration Scanner**

````markdown
# Docker Container Misconfiguration Scanner

## Overview

A Python script that statically analyzes Dockerfiles to identify common container security misconfigurations.

The scanner checks for insecure Docker build practices and reports potential security risks.

## Features

- Detects usage of `latest` tag
- Checks for missing USER instruction
- Detects exposed SSH port (22)
- Simple static analysis
- Lightweight implementation

## Technologies Used

- Python 3

