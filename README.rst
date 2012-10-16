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
- For the soure code: `Inconsolata <http://www.google.com/webfonts/specimen/Inconsolata>`_

Preview
-------

.. image:: https://raw.github.com/gist/3885420/1bcd46f617947e79f7fd4543ae82a9edd5d21344/iris_small.png
    :align: center

Variables
---------

Some of the variables that could be used:

- ``DISQUS_SITENAME``: For the disqus comments
- ``GOSQUARED_SITENAME``: For the Go squared analytics
- ``EMAIL``: For the email "mailto:"

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
