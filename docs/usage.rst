=====
Usage
=====

To use Wagtail SEO Page in a project, add it to your `INSTALLED_APPS`:

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
