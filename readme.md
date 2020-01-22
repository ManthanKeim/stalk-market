# Stalk Market

Stalk Market is a trade off platform built with the use of web app built in Python with Flask, SQLAlchemy & AngularJS. 

## Contents
- Tech Stack
- Installation

## Tech Stack

Backend: Python, Flask, PostgreSQL, SQLAlchemy

Frontend: Javascript, HTML, jQuery, AJAX, HTML5, CSS3, Bootstrap

Azure Services: Web Apps, Azure SQL Database

## Installation

Install PostgreSQL

To create and activate a virtual environment:
```
virtualenv env
source env/bin/activate
```

To install the project's dependencies:
```
pip install -r requirements.txt
```

To recreate the database:
```
createdb shop --encoding='utf-8' --locale=en_US.utf8 --template=template0
pg_restore shop database.sql
```

Create a secrets.sh file:
```
export EDAMAM="YOURKEYHERE"
export EDAMAM_KEY="YOURKEYHERE"
export STRIPE_TEST_SECRET="YOURKEYHERE"
export STRIPE_TEST_PUBLISHABLE="YOURKEYHERE"
export STRIPE_LIVE_SECRET="YOURKEYHERE"
export STRIPE_LIVE_PUBLISHABLE="YOURKEYHERE"
export GOOGLE_MAPS_KEY="YOURKEYHERE"
```

And source it:
```
source secrets.sh
```


Microsoft Hacks
