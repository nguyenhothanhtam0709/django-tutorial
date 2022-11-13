# Overview

Simple RESTful api written in Django

## Setup

```bash
# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependency
pip install -r requirements.txt

#
python manage.py migrate
python manage.py runserver
```
