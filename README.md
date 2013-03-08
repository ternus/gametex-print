GameTeX Django Print
====================

A Django app for generating and managing PDFs from GameTeX.  Writing a ten-day webapp?  You'll want this (too).

Getting started
---------------

To install:

* `pip install gametex-django-print` 
* Add `gametex_django_print` to your `INSTALLED_APPS` in settings.py.
* Add `GAMETEX_PROJECT_ROOT=/path/to/your/game/` and `GAMETEX_NAME=gamename` (should match what you have in your dotfiles)
* Add `url(r'^gametex/$', include('gametex_django_print.urls')),` or similar to your Django urls.py.
