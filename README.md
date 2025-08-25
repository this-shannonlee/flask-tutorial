# flask-tutorial
Tutorial - [https://flask.palletsprojects.com/en/stable/tutorial/](https://flask.palletsprojects.com/en/stable/tutorial/)  
Quickstart - [https://flask.palletsprojects.com/en/stable/quickstart/](https://flask.palletsprojects.com/en/stable/quickstart/)

- Create and clone github repository with Python .gitignore.
- Navigate to repository directory.
- Create virtual environment.
- Activate virtual environment.
- Install Flask
    ```
    pip install Flask
    ```
- Create and navigate to project directory
- Create `__init__.py`. Add application factory function.
- Run application from repository root directory.
    ```
    flask --app flaskr run --debug
    ```
- Create database connection in ```db.py``` . Include function to intialize the database.
- Create database schema in ```schema.sql```
- Add db import and database initialization function call to application factory in ```__init.py__```
- Run command to initialize database.
    ```
    flask --app flaskr init-db
    ```
- Create __auth__ blueprint and views in ```auth.py```.
- Create __auth__ templates.
- Add css file to __static__ directory.
- Create __blog__ blueprint, views and templates.