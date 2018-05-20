## Getting started

1. Install `brew`
1. Install `pip`
1. Install `virtualenv` and `virtualenvwrapper`
1. Add `virtualenvwrapper` to your path

## Development

1. Active the virtualenv: `workon superlists`
1. Create the database: `python manage.py migrate`
1. Start the development server: `python manage.py runserver`
1. Execute unit and functional tests: `python manage.py test`

## Refactoring

1. Get a list of all the test classes and methods: `grep -E "class|def" lists/tests.py`