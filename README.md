# Planetarium

System for managing an astronomy show

## Installation

Python3 must be already installed


For Windows
```shell
git clone https://github.com/yaroslav-mazurkevych/Planetarium.git
cd Planetarium
python3 -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
python manage.py loaddata db_data.json # load data from json
python manage.py runserver # starts Django server
```

For Mac(Linux)
```shell
git clone https://github.com/yaroslav-mazurkevych/Planetarium.git
cd Planetarium
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py loaddata db_data.json # load data from json
python manage.py runserver # starts Django server
```

## Features

* JWT Authentication functionality for User
* Managing astronomy shows and reservations directly from website interface
* Admin panel for advanced managing
* Create astronomy shows with show themes
* Filtering astronomy shows and show sessions

## DB structure

![img.png](img.png)


## Demo

![img_1.png](demo_image/img_1.png)