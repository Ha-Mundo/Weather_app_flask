# Weather_app_flask
Weather Flask-Sqlalchemy application that use an API-Key from openweathermap.org and  Sqlite3 local database.

1-Create a virtual enviroment with: pip3 install pipenv

2-Install all the dependencies and packages: pip install -r requirements.txt

3-Put your API-KEY fromopenweathermap.org in the main router inside app.py

4-Create your database:  1)sqlite3 weather.db
                         2).tables
                         3).exit
                         
5- Open the Python shell from the terminal: 1)python
                                            2)from app import db
                                            3)db.create_all()
                                            4)exit()


6- flask run
