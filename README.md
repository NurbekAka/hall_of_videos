
### Crowdsourcing platform for translation from any language to Kyrgyz
#### To run this project:
* Clone this repository
```
git clone git@github.com:NurbekAka/hall_of_videos.git
```

* Activate virtual environment:
```
pip install pipenv
pipenv --python 3
pipenv shell
pipenv install
```

* This project uses db.sqlite3, so you will have to enter directly commands.
 
 ```
 python manage.py makemigrations
 python manage.py migrate
 python manage.py createsuperuser
 ```
 
* Finally, run project with command: `python3 manage.py runserver`


* PROFIT!
______________________
