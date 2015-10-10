.. _install:


Installation guide
==================

.. warning::

   ``django-registration`` |version| is **in development and not yet
   released. The latest released version is still 1.0.** To install
   ``django-registration`` |version|, you will need to follow the
   instructions in the section "Installing from a source checkout."
   Attempting to install from the Python Package Index will not work
   until ``django-registration`` |version| has been released.

Before installing ``django-registration``, you'll need to have a copy
of `Django <https://www.djangoproject.com>`_ already installed. For
information on obtaining and installing Django, consult the `Django
download page <https://www.djangoproject.com/download/>`_, which
offers convenient packaged downloads and installation instructions.

The |version| release of ``django-registration`` supports Django 1.7
and 1.8, on any Python version those versions of Django support
(officially, Python 2.7, 3.3 and 3.4). Additionally, as Python 3.5 was
released while ``django-registration`` |version| was being developed,
it is compatible with Python 3.5, though Django itself will not
officially support Python 3.5 until Django 1.9, and Django 1.7 is
known to be explicitly incompatible with Python 3.5.


Normal installation
-------------------

The preferred method of installing ``django-registration`` is via
``pip``, the standard Python package-installation tool. If you don't
have ``pip``, instructions are available for `how to obtain and
install it <https://pip.pypa.io/en/latest/installing.html>`_.

Once you have ``pip``, simply type::

    pip install django-registration


Manual installation
-------------------

It's also possible to install ``django-registration`` manually. To do
so, obtain the latest packaged version from `the listing on the Python
Package Index
<https://pypi.python.org/pypi/django-registration/>`_. Unpack the
``.tar.gz`` file, and run::

    python setup.py install

Once you've installed ``django-registration``, you can verify
successful installation by opening a Python interpreter and typing
``import contact_form``.

If the installation was successful, you'll simply get a fresh Python
prompt. If you instead see an ``ImportError``, check the configuration
of your install tools and your Python import path to ensure
``django-registration`` installed into a location Python can import
from.


Installing from a source checkout
---------------------------------

The development repository for ``django-registration`` is at
<https://github.com/ubernostrum/django-registration>. Presuming you
have `git <http://git-scm.com/>`_ installed, you can obtain a copy of
the repository by typing::

    git clone https://github.com/ubernostrum/django-registration.git

From there, you can use normal git commands to check out the specific
revision you want, and install it using ``python setup.py install``.


Next steps
----------

To get up and running quickly, checkout :ref:`the quick start guide
<quickstart>`. For full documentation, see :ref:`the documentation
index <index>`.