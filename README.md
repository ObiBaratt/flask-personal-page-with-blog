# Flask Blog Backend
This is the backend for a personal webpage with an integrated blog built with Flask, and PostgreSQL. The frontend for this project can be anything, and currently has flask_bootstrap setup. This is a great starting point to learn HTML/CSS with Bootstrap by using Flask's built in Jinja templating engine to display backend data. I found that people I've mentored responded much better to learning frontend foundations by utilizing this project instead of building yet another website with HTML/CSS that doesn't really do anything.

## Utiliizing this Code:
- Make sure you have Python installed
- Pick your favorite editor, I like [PyCharm](https://www.jetbrains.com/pycharm/)  and [Visual Stuido Code](https://code.visualstudio.com/).
- Setup a [virtual environment.](https://realpython.com/python-virtual-environments-a-primer/)
- From the root of the project, install the requirements: ```pip install -r requirements.txt```
- Add your Flask Key ( as 'SECRET_KEY' ) and your Postgres db url (as 'PG_DB_URL' ) into environ.
- Setup app.py as your main file.
- Setup the Admin account (currently setup to be the first registered user in app.py ln 82) before making the site live! You can also change this logic to have the admin check based on current_user.email with an approved email list for example.
- The included Procfile is for [Heroku](https://www.heroku.com/) deployments. Note Heroku is no longer free but it is very easy to deploy on.
