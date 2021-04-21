is-number
=========

.. image:: https://github.com/thomasarsouze/is-number/actions/workflows/ci.yaml/badge.svg
    :target: https://github.com/thomasarsouze/is-number/actions/workflows/ci.yaml
    :alt: GitHub Actions - CI
.. image:: https://github.com/thomasarsouze/is-number/actions/workflows/pre-commit.yaml/badge.svg
    :target: https://github.com/thomasarsouze/is-number/actions/workflows/pre-commit.yaml
    :alt: GitHub Actions - pre-commit
.. image:: https://img.shields.io/codecov/c/gh/thomasarsouze/is-number
    :target: https://app.codecov.io/gh/thomasarsouze/is-number
    :alt: Codecov
A Python library to determine if something is a number.

Developing
----------

This project uses ``black`` to format code and ``flake8`` for linting. We also support ``pre-commit`` to ensure
these have been run. To configure your local environment please install these development dependencies and set up
the commit hooks.

.. code-block:: bash

   $ pip install black flake8 pre-commit
   $ pre-commit install

Testing
-------

This project uses ``pytest`` to run tests and also to test docstring examples.

Install the test dependencies.

.. code-block:: bash

   $ pip install -r requirements_test.txt

Run the tests.

.. code-block:: bash

    $ pytest
    === 3 passed in 0.13 seconds ===
