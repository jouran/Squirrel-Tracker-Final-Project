# IEOR 4501 Final Project
# Squirrel Tracker


## Introduction

We used Django, a web-application tool which is able to accomplish data import/export, manipulation, and visualization, and implemented a Squirrel Tracker indicating sightings of squirrels found in Central Park of New York City in Python and HTML.


## DataSet
For this project, [**2018 Central Park Squirrel Census**](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw) dataset from [**Squirrel Census**](https://www.thesquirrelcensus.com/) was used.  
This dataset contains 3023 sightings, including location coordinates, age, primary and etc. 


## Management Commands
Import: 

```sh
python manage.py import_squirrel_data /path/to/file.csv
```

Export: 

```sh
python manage.py export_squirrel_data /path/to/file.csv
```


## Dependencies
- [Django](https://www.djangoproject.com)
- [Django-Leaflet](https://django-leaflet.readthedocs.io/en/latest/)  

## Documentation
The official description for this project is in 
[**Squirrel Tracker**](https://docs.google.com/document/d/1SPv3fMDKiemrR86rD-S9ecvI2npz3PljDzwCfxK2x5g/edit)

## Background
Eccentric billionaire Joffrey Hosencratz just purchased the web development company you work for. You’ve met him once in an elevator and he was impressed with your skill in developing web applications with the ``Django`` framework. He also relayed that his most recent trip to Sedona, AZ has left him in a bit of trouble. See, he fancies the show Rick and Morty and a particular scene coupled with a traumatic childhood squirrel experience and a bad crystal bath experience in Sedona as left him wanting. 

He would like to start keeping track of all the known squirrels and plans to start with Central Park. He’s asked you to build an application that can import the 2018 Central Park Squirrel Census data and allow his team to add, update, and delete squirrel data. 


## Contributors
Contributors: Zheyuan Hu, Yang Rong

UNIs: zh2447, yr2387
