{% comment "This comment section will be deleted in the generated project" %}

# [django-perfect-start][docs]

[![Build Status](https://travis-ci.org/konoufo/edge.svg?branch=master)](https://travis-ci.org/konoufo/edge)

**Django project starter template for general purpose webapp.**

## Features

* Ready Bootstrap-themed pages
* User Accounts made easy
* Better Security with [12-Factor](http://12factor.net/) recommendations 
* Logging/Debugging Helpers
* Python 3.5 / Django 1.11
* Webpack 2.0, best/easiest assets management for your project (with configurations for both development and production)

## Quick start:

1. `$ django-admin.py startproject --template=https://github.com/konoufo/edge/archive/master.zip --extension=py,md,html,env my_proj`
2. `$ cd my_proj`
3. `$ pip install -r requirements.txt `
4. `$ npm i`
5. `$ cp src/my_proj/settings/local.sample.env local.env`
6. `$ cd src`
7. `$ python manage.py migrate`

More information at: [http://django-edge.readthedocs.org/][docs]


[docs]: http://django-edge.readthedocs.org/

Rest of this README will be copied to the generated project.

--------------------------------------------------------------------------------------------

{% endcomment %}

# {{ project_name }}

{{ project_name }} is a _short description_. It is built with [Python][0] using the [Django Web Framework][1].

This project has the following basic apps:

* App1 (short desc)
* App2 (short desc)
* App3 (short desc)

## Installation

### Quick start

To set up a development environment quickly, first install Python 3. It
comes with virtualenv built-in. So create a virtual env by:

    1. `$ python3 -m venv {{ project_name }}`
    2. `$ . {{ project_name }}/bin/activate`

Install all dependencies:

    pip install -r requirements.txt
    npm i

Run migrations:

    python manage.py migrate

### Detailed instructions

Take a look at the docs for more information.

[0]: https://www.python.org/
[1]: https://www.djangoproject.com/
