Django - Snapshot Publisher
=============================

Django Appplication API to store  and get Document for a release

Quick start
-----------

1. Add "djangosnapshotpublisher" to your INSTALLED_APPS setting like this:

```python
INSTALLED_APPS = [
    'djangosnapshotpublisher',
    ...
]
```

2. Run `python manage.py migrate` to create the djangosnapshotpublisher models.


How to use
----------

Read the [documentation guide][docs-index]


How to contribute
-----------------

### Requirements
* Docker
* docker-compose
You'll get all this lot installed nicely with (https://docs.docker.com/docker-for-mac/install).


### Setup locally
Build the image
```
docker-compose build
```
Run the containers
```
docker-compose up
```
Create super user:
```
docker-compose run --rm web python manage.py createsuperuser
```

[docs-index]: https://github.com/yohanlebret/django-snapshotpublisher/blob/master/docs/index.md