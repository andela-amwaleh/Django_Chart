## Graph

This Django app uses jS to generate Graphs.


Currently it reads from a json file and uses ajax to draw the information.

### Load data into database
use fixture to load the data
- run migrations
- Next, load sample data by running.
```python

$ python manage.py loaddata app_population.json

```
