====
Iris
====

What is iris?
-------------

Iris is a `pelican <http://getpelican.com>`_ theme based on `Flask webpage <http://flask.pocoo.org/>`_ Also uses various fonts. This are:

- For social icons: `Font awesome <http://fortawesome.github.com/Font-Awesome/>`_
- For the title: `The girl next door <http://www.google.com/webfonts/specimen/The+Girl+Next+Door>`_
- For the soure code: `Inconsolata <http://www.google.com/webfonts/specimen/Inconsolata>`_

Preview
-------

.. image:: https://raw.github.com/gist/3885420/1bcd46f617947e79f7fd4543ae82a9edd5d21344/iris_small.png
    :align: center

Variables
---------

Some of the variables that could be used are:

- ``DISQUS_SITENAME``: For the disqus comments
- ``GOSQUARED_SITENAME``: For the Go squared analytics

Installation
------------

To install, insert in your pelican theme directory and clone the repo. For 
example::
    
    $ cd /home/slok/.virtualenvs/blog/lib/python2.7/site-packages/pelican/themes/
    git clone https://github.com/slok/iris.git

the set the variable ``THEME`` to ``iris`` like this::

    THEME = "iris"

License
-------

This theme is under the `3 clause BSD license <http://opensource.org/licenses/bsd-3-clause>`_
