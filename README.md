# First Python Project

# Setup Guide

## Check Python installed

    # Check python version
    python --version

## Recreating the Environment

When someone clones your repository, they can create their own virtual environment and install the dependencies listed in requirements.txt

    # Create the virtual environment
    python -m venv venv

    # Activate the environment (Linux/macOS)
    source venv/bin/activate

    # Activate the environment (Windows)
    venv\Scripts\activate

    # Install dependencies
    pip install -r requirements.txt

# Commit Guide

After activating your virtual environment and installing all necessary packages, export a list of these dependencies and their versions to a requirements.txt file.

    pip freeze > requirements.txt

_Commit_ the **requirements.txt**
