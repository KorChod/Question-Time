# Question-Time
Question Time is a forum site where users can share knowledge, ask questions and post answers.

I made this project as a part of my Django and Vue.js practice.

## Features
- user registration
- user login
- users can start new threads
- users can answer to existing questions
- answer like/dislike option
- owners can edit and delete their questions and answers
- there is and admin site where admins can manage site resources

## Setup
The site was made in Django. Start creating virtual environment for this project.

`virtualenv venv`

Then install all the packages from `requirements.txt`

`pip install -r requirements.txt`

This project has a separate frontend made in Vue.js. To make it work, please make sure you have installed `vue cli` (Vue Command Line) and `npm` (Node Package Manager) from `https://nodejs.org/en/`.

Having it installed, go to source root of your Django application and run command `django-admin runserver`.

In another terminal window go to `frontend` directory and run command `npm run serve` to run your front-end server.

You will be welcomed by a login window. Only singed in users can browse the site therefore please create an account before you start.

This app is using sqlite3 database and doesn't require any additional configuration of the database except having `db.sqlite3` file in the root folder.  
