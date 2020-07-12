Workouts on a Django tutorial, extracted from https://github.com/mytinylabo/python-crash-course to deploy the app to Heroku.

## Note
When using Pipenv to bring up a virtual environment for the project, ignore the steps to prepare `requirements.txt` and `runtime.txt` in *"Deploying Lerning Log"* in Chapter 18.
Instead Heroku will refer to `Pipfile.lock`, which Pipenv automatically maintains, to resolve dependencies.
