# Flask Blog Backend
This is the backend for a personal webpage with an integrated blog built with Flask, and PostgreSQL. The frontend for this project can be anything, and currently has flask_bootstrap setup. This is a great starting point to learn HTML/CSS with Bootstrap by using Flask's built in Jinja templating engine to display backend data. I found that people I've mentored responded much better to learning frontend foundations by utilizing this project instead of building yet another website with HTML/CSS that doesn't really do anything.

This code demonstrates relational database design, ORM utilization (SQLAlchemy), and a backend project as my current work is very React heavy or built with serverless backends using GCP. While I love the ability to use 

## Utiliizing this Code:
- Setup a Flask project with proper directories that are missing here (static, templates).
- Add your Flask Key ( as 'SECRET_KEY' ) and your Postgres db url (as 'PG_DB_URL' ) into environ.
- Setup app.py as your main file.
- Add inputcleaner.py and forms.py (you can organize them however you want, just make sure to change the import statements in app.py).
- Setup the Admin account (currently setup to be the first registered user in app.py ln 82) before making the site live! You can also change this logic to have the admin check based on current_user.email with an approved email list for example.
