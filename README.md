![Django Logo](https://www.djangoproject.com/m/img/logos/django-logo-positive.png)

# Django Starter Template

This repository contains a template skeleton for Django Projects which includes debug_toolbar and django-environ

## Table of Contents

- [Requirements](#requirements)
  - [Installation](#installation)
- [Authors](#authors)

## Requirements

- Python 3.6+
- Django 3.0+

### Installation

- On your terminal, clone the repository with Git:

`git clone https://github.com/rmiyazaki6499/django_starter.git`

- In order to install Python dependencies, make sure you have pip (https://pip.pypa.io/en/stable/installing/)
and run this command from the root of the repo:

`pip3 install -r requirements.txt`

- To run the development server, use the following command:

`python3 manage.py runserver`

Navigate to http://localhost:8000 to view the development site.

- To run the production server, use the following command:

`ENV_PATH=.env-prod python3 manage.py runserver`


## Authors

Created by:

- [Ryuichi Miyazaki](https://github.com/rmiyazaki6499)
