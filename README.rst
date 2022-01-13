*************************
PySAML2 - SAML2 in Python 2.7
*************************

:Version: see VERSION_
:Documentation: https://pysaml2.readthedocs.io/

**This is a Python 2.7 fork of PySAML2. It will be updated to match IdentityPython/pysaml2 master from time to time.**

PySAML2 is a pure python 2.7 implementation of SAML Version 2 Standard. It contains
all necessary pieces for building a SAML2 service provider or an identity
provider. The distribution contains examples of both. Originally written to
work in a WSGI environment there are extensions that allow you to use it with
other frameworks.

Install
=======
You can install with `pip install pysaml2`

Testing
=======

PySAML2 uses the pytest_ framework for testing. To run the tests on your
system's version of python:

1. Create and activate a virtualenv_
2. Inside the virtualenv_, install the dependencies needed for testing
   :code:`pip install -r tests/test-requirements.txt`
3. Run the tests :code:`py.test tests`

To run tests in multiple python environments, you can use pyenv_ with tox_.


Please contribute!
==================

To help out, you could:

1. Test and report any bugs or other difficulties.
2. Implement missing features.
3. Write more unit tests.

**If you have the time and inclination I'm looking for Collaborators**


.. _VERSION: VERSION
.. _pytest: https://docs.pytest.org/en/latest/
.. _virtualenv: https://virtualenv.pypa.io/en/stable/
.. _pyenv: https://github.com/yyuu/pyenv
.. _tox: https://tox.readthedocs.io/en/latest/
