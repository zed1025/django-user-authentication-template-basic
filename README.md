# django-user-authentication(basic)

## A simple basic authentication template. This app can be used as a base, or starting point for other projects. The technique used for authentication is by extending the `AbstractUser` class provided by django. So the security is not at a level that this can be used in production. Use this for hobby or personal projects, for production I would advise to try __token based authentication__ or use django packages like **django-allauth** in combination with **django-rest-auth**

## Requirements
- [django-crispy-forms](https://django-crispy-forms.readthedocs.io/en/latest/)
- Tested on 
    - python3.7
    - django3.0.1
    - django-crispy-forms1.9.2
- bootstrap4


## Features
- navbar
- login
- signup
- password change
- password reset(using terminal)