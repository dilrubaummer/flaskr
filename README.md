# flaskr
creating a basic blog application called Flaskr. Users will be able to register, log in, create posts, and edit or delete their own posts
python3 -m venv venv
source venv/bin/activate
flask --app flskr run --debug 

init-db that calls the init_db function

flask --app flskr init-db
Initialized the database.
# The application will use a SQLite database to store users and posts. Python comes with built-in support for SQLite in the sqlite3 module.