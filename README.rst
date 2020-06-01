=============================
Wagtail SEO Page
=============================

.. image:: https://badge.fury.io/py/wagtail-seopage.svg
    :target: https://badge.fury.io/py/wagtail-seopage

.. image:: https://travis-ci.org/techequipt/wagtail-seopage.svg?branch=master
    :target: https://travis-ci.org/techequipt/wagtail-seopage

.. image:: https://codecov.io/gh/techequipt/wagtail-seopage/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/techequipt/wagtail-seopage

Your project description goes here

Documentation
-------------

The full documentation is at https://wagtail-seopage.readthedocs.io.

Quickstart
----------

Install Wagtail SEO Page::

    pip install wagtail-seopage

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'wagtail_seopage.apps.WagtailSeopageConfig',
        ...
    )

Add Wagtail SEO Page's URL patterns:

.. code-block:: python

    from wagtail_seopage import urls as wagtail_seopage_urls


    urlpatterns = [
        ...
        url(r'^', include(wagtail_seopage_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
