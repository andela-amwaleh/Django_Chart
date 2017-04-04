## Graph
![](https://cdn.scotch.io/15775/OQk6534nTPCqvZOaJg1I_Screen%20Shot%202017-03-20%20at%2012.42.55%20AM.png)
This Django app uses chartjS to generate Graphs.


Currently it  uses ajax to draw the information from the Database.

clone this repo
```Bash
 git clone git@github.com:andela-amwaleh/Django_Chart.git

```

**Create a virtualenv**
### Install dependencies
```bash
    pip install -r requirements.txt

```
### Load data into database
use fixture to load the data
- run migrations
```Bash
 cd Django-Chart
 python manage.py makemigrations
 python manage.py migrate
```
- Next, load sample data by running.
```Bash

$ python manage.py loaddata app_sample_data.json

```
- Start the server

```Bash

$ python manage.py runserver

```

- Navigate to http://localhost:8000 in your browser
