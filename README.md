# Cookiecutter Template for Python Library

This Cookiecutter template helps you quickly set up a new library project in Python, following best practices and a consistent project structure.

## Table of Contents

- [Cookiecutter Template for Python Library](#cookiecutter-template-for-python-library)
  - [Table of Contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Usage](#usage)
  - [Project Structure](#project-structure)

## Requirements

- Python 3.6 or higher
- [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html) installed

## Usage

To create a new project using this Cookiecutter template, follow these steps:

1. **Install Cookiecutter** (if not already installed):

    ```bash
    pip install cookiecutter
    ```

2. **Generate a New Project**:

    ```bash
    cookiecutter https://github.com/yourusername/cookiecutter-python-project-lib.git
    ```

3. **Follow the Prompts**: You will be prompted to enter various details about your project, such as the project name, author name, version, and description.

4. **Navigate to the Project Directory**:

    ```bash
    cd your_project_name
    ```

5. **Install the Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

6. **Pre-commits**
```bash
pip install pre-commit
pre-commit install
pre-commit clean
pre-commit run --all-files
```
...


## Project Structure

The generated project will have the following structure:

