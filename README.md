# Simple Ecommerce

[![Python Version](https://img.shields.io/badge/python-3.5-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-2.0-brightgreen.svg)](https://djangoproject.com)

An extremely simple ecommerce application written in Django.

To install the project follow these steps:

1. `git clone https://github.com/overiq/simple_ecommerce.git`.
1. `cd simple_ecommerce`
1. `virtualenv env`
1. `source env/bin/activate` (for Linux/Mac OS ) or `env\Scripts\activate.bat` (for Windows)
1. `pip install -r requirements.txt`
1. `cd django_project/`
1. `python manage.py migrate`
1. `python manage.py runserver`



Cloning a repository:
  git clone https://github.com/overiq/simple_ecommerce.git

Forking a repository
  https://github.com/ogutujean/simple_ecommerce.git

Cloning the forked repo
  git clone https://github.com/ogutujean/simple_ecommerce.git

Creating and Switching Branches
  git checkout -b feature-update

Made an addition of welcome message to the templates(index.html) file as h2

Committed changes : first by staging the changes : git add .
                    Then by commiting :git commit -m "Added Welcome message the indexfile in templates"

Switched back to the master branch: git checkout master

Merged the changes of the feature-update branch: git merge feature-update

Creating conflict in my forked repo: first added the welcome message in the index.html file and commited it as "updateindex.html".

Creating and switching to a new branch called conflict-resolution: git checkout -b conflict-resolution

In my file in vs code i deleted the welcome message in the index.html

I staged and commited the changes: git add .   then     git commit -m "Resolving the conflict by removing the welcome message"

I returned to my master branch and merged the new branch: git checkout master     then    git merge conflict-resolution

created a new file in my github repo called file.html

Enabled github pages and set the source to master

Accesing the published page : https://ogutujean.github.io/simple_ecommerce/

I explored source projects and read the documentation, browsed the issues, and reviewed the contribution guidelines.

 I Opened a new issue in the open-source projectand  requested for clarification

 I pushed my changed to the github repo : git push origin master








