# TheBook.co.il Project Setup Guide

Welcome to the setup guide for TheBook.co.il project. This guide will help you get your development environment ready in a few simple steps.

## 📋 Prerequisites

- A system capable of running Python (Windows, macOS, Linux).
- Git for version control.

## 🛠️ Installation Steps

### 1️⃣ Install Python 3.11.4

1. Visit the [official Python website](https://www.python.org/downloads/).
2. Download and install **Python 3.11.4**.
3. To verify the installation, open a terminal or command prompt and run:
`python3 --version`
You should see `Python 3.11.4`.

### 2️⃣ Clone the Repository

Clone the project from GitHub:
`git clone https://github.com/RuslanKovalyov/TheBook.git`
and navigate to the project directory:
`cd TheBook`

### 3️⃣ Create a Virtual Environment

Using the `venv` module, set up a virtual environment:
`python3.11 -m venv venv`
This command creates a new virtual environment named `venv`.

### 4️⃣ Activate the Virtual Environment

- On **macOS and Linux**:
`source venv/bin/activate`

### 5️⃣ Install Required Packages

Install the necessary packages:
`pip install --upgrade pip`
`pip install -r requirements.txt`
This command will install Django 4.2.4 and any other dependencies.

### 6️⃣ Begin Development

You're all set! Start your development, run migrations, or launch the Django development server.

### 7️⃣ Deactivate the Virtual Environment

When you're done with your development tasks, you can deactivate the virtual environment:
`deactivate`
