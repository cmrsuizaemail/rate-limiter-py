# rate-limiter-py

This
The unit tests are run with [nose](http://nose.readthedocs.io/en/latest/) inside a virtual environment managed
by [tox](https://pypi.python.org/pypi/tox). The `test_requirements.txt` contains all the testing dependencies and
is used to pip install everything needed by the tests in the tox environments (tox installs these dependencies).

### Code Hygiene
The `make check` command will run [pylint](https://www.pylint.org/) with standards defined in `pylintrc`.
This is a measurable way to enforce style and standards.

### Cleanup
Run `make clean` to remove artifacts leftover by tox and pylint.
