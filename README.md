# AdoptTrack Backend

This guide will help you set up a Django development environment on Linux, macOS, and Windows. It covers the installation of essential tools and provides step-by-step instructions for each operating system.

## Table of Contents
1. [Common Tools](#common-tools)
2. [Linux Setup](#linux-setup)
3. [macOS Setup](#macos-setup)
4. [Windows Setup](#windows-setup)
5. [Final Steps](#final-steps)

## Common Tools

Regardless of your operating system, you'll need the following tools:

- Python (3.8 or higher)
- pip (Python package manager)
- virtualenv (for creating isolated Python environments)
- Git (for version control)
- A text editor or IDE (e.g., Visual Studio Code, PyCharm, Sublime Text)

## Linux Setup

### Ubuntu/Debian

1. Update package list:
   ```bash
   sudo apt update
   ```

2. Install Python and pip:
   ```bash
   sudo apt install python3 python3-pip
   ```

3. Install Git:
   ```bash
   sudo apt install git
   ```

4. Install virtualenv:
   ```bash
   sudo pip3 install virtualenv
   ```

### Fedora/CentOS

1. Update package list:
   ```bash
   sudo dnf update
   ```

2. Install Python and pip:
   ```bash
   sudo dnf install python3 python3-pip
   ```

3. Install Git:
   ```bash
   sudo dnf install git
   ```

4. Install virtualenv:
   ```bash
   sudo pip3 install virtualenv
   ```

## macOS Setup

### 1. Install Homebrew

Homebrew is a package manager for macOS that makes it easy to install software.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 2. Install Python

```bash
brew install python
```

### 3. Install Git

```bash
brew install git
```

### 4. Install virtualenv

```bash
pip3 install virtualenv
```

## Windows Setup

### 1. Install Python

1. Download Python from the [official website](https://www.python.org/downloads/windows/).
2. Run the installer, ensuring you check "Add Python to PATH".

### 2. Install Git

1. Download Git from the [official website](https://git-scm.com/download/win).
2. Run the installer, using the default options.

### 3. Install virtualenv

Open Command Prompt and run:

```bash
pip install virtualenv
```

## Final Steps

After installing the necessary tools, follow these steps to set up your Django project:

1. Create a project directory:
   ```bash
   mkdir mydjangoproj
   cd mydjangoproj
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:
   - On Linux and macOS:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

4. Install Django:
   ```bash
   pip install django
   ```

5. Start a new Django project:
   ```bash
   django-admin startproject mysite
   ```

6. Navigate to the project directory and run the development server:
   ```bash
   cd mysite
   python manage.py runserver
   ```

You should now see a message indicating that the Django development server is running. Open a web browser and go to `http://127.0.0.1:8000` to see your Django project in action!

Remember to always activate your virtual environment before working on your Django project.

### Additional Tips

- Use `requirements.txt` to manage project dependencies:
  ```bash
  pip freeze > requirements.txt
  ```
  To install dependencies on another machine:
  ```bash
  pip install -r requirements.txt
  ```

- Set up a `.gitignore` file to exclude unnecessary files from version control.

- Consider using a database like PostgreSQL for production environments.

- Familiarize yourself with Django's documentation and tutorials for best practices in web development.
