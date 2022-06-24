# Steps to set up the project

## Initial set up for development
* set up a virtual environment for the project
      `python -m venv jackmanimation_website_env`
* set the environment going
      `jackmanimation_website\scripts\activate`
* install Django 3
      `pip install "django>3,<4"`

## Set up the Django Project
* create a default django project
      `django-admin startproject jackmanimation_site`
* step into the site directory
      `cd jackmanimation_site`
* create a database for the site
      `python manage.py migrate`
* run the server to confirm it is all ok
      `python manage.py runserver`
* While the server is running go to [site](http://127.0.0.1:8000) and check it out. If the server is not running it will error out.
*   Check the code into the version control and use your CI/CD process on it. Ensure that it is  <b style='color:green'>GREEN</b>. This is in [Jackmanimation Website Project](https://github.com/Jackmanimation/Jackmanimation-website)

## References
* [Django Tutorial](https://djangobook.com/django-tutorial-for-beginners/)
