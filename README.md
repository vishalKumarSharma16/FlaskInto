# This is my First Flask application 

## installation
```
git clone https://github.com/vishalKumarSharma16/FlaskIntro.git
cd FlaskIntro.git
virtualenv env
source env/bin/activate
pip install -r requirements.in
python app.py
```

## creating database
go to FlaskIntro directory
```
python3
from app import db
db.create_all()
exit()

python app.py
```

It will run on localhost:5000

## Deploying to heroku
> heroku login
> heroku create todo --buildpack heroku/python

