====
Iris
====

What is iris?
-------------

Iris is a `pelican <http://getpelican.com>`_ theme based on `Flask webpage <http://flask.pocoo.org/>`_ 
This theme is very simple and easy to read, perfect for a minimalist blog without much things and
beautiful source code syntax (Thank you `pygments <http://pygments.org/>`_!)
Also uses various fonts:

- For social icons: `Font awesome <http://fortawesome.github.com/Font-Awesome/>`_
- For the title: `The girl next door <http://www.google.com/webfonts/specimen/The+Girl+Next+Door>`_
- For the headers: `Marcellus <http://www.google.com/webfonts/specimen/Marcellus>`_
- For the soure code: `Inconsolata <http://www.google.com/webfonts/specimen/Inconsolata>`_

Preview
-------

.. image:: https://raw.github.com/gist/3885420/bbb0c9598f32a7913b16f4ea4c0308e8c701ef9b/iris_marcellus.png
    :align: center

Variables
---------

Some of the variables that could be used:

- ``DISQUS_SITENAME``: For the disqus comments
- ``EMAIL``: For the email "mailto:"

For the analytics we have two flavours, one is Go `Squared <https://www.gosquared.com>`_

- ``GOSQUARED_SITENAME``: For the Go squared analytics

And the other is `Google analytics <https://www.google.com/analytics>`_ Google analytics has various forms. The
basic one is:

- ``GOOGLE_ANALYTICS_CODE``: this is the code of GA, something similar to: ``UA-xxxxxxxx-y``

If you have analytics across domains you can put this setting:

- ``GOOGLE_ANALYTICS_DOMAIN = "xlarrakoetxea.org"``

And if you have upper domain level (com, org, co.uk...)

- ``GOOGLE_ANALYTICS_DOMAIN_UP = True``

Installation
------------

To install, go to your pelican theme directory and clone the repo. For 
example::
    
    $ cd /home/slok/.virtualenvs/blog/lib/python2.7/site-packages/pelican/themes/
    $ git clone https://github.com/slok/iris.git

Set the variable ``THEME`` to ``iris`` in your pelican settings, like this::

    THEME = "iris"

Notes
-----

The theme navigation bar does a fade in if you scroll more than 300 pixels to
increase the readability of an article.

ReStructuredText creates ``tt`` with ````something```` that is equivalent to  markdown ``code``
that is created wit ```something```. This renders inline source code. So I added ``tt`` to the
css also, not only ``code`` like most themes. Example:


.. image:: https://raw.github.com/gist/3885420/4d7a8557780ab74c5ae797a4f6e82cbf11aec0c6/iris_inline.png
    :align: center

License
-------

This theme is under the `3 clause BSD license <http://opensource.org/licenses/bsd-3-clause>`_
