Reina Valera Gómez Django-Bibletext Viewer App
==============================================

A Django app for the full Reina Valera Gómez Bible text.

Plugs into the Django-Bibletext App and provides the full
Reina-Valera Gómez text.

You can see it in action [here.](http://westcoastbaptistkjv.org/bible/RVG/)

Dependencies
------------

Uses [django-bibletext](http://github.com/richardbolt/django-bibletext) for
the core functioality. You will need that on your path somewhere.

Django-Bibletext uses [python-bible](http://github.com/jasford/python-bible) for
computing and handling the verse and passage lookups. You will need that
on your path somewhere. This dependency will possibly be removed in the future.

Installation
------------

* Make sure the dependencies are satisfied and this module is somewhere on your python path.
* Add `'rvg'` to your `INSTALLED_APPS` in your **settings.py**.
* Create your database tables: `python manage.py syncdb`.
* Install initial data from fixtures: `python manage.py loaddata rvg.json`.

Usage
-----

See [django-bibletext](http://github.com/richardbolt/django-bibletext) for usage details.