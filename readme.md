CorruptionReporter
A web based system for reporting on corruption and public services needs and requests.

CorruptionReporter is a web based platform that enables any/every citizen to bring any form of corruption to the notice of appropriate authorities and thegeneral public. Users can also report on things that need government intervention such as public works or repairs.

to make sure all the packages needed to run the project present in your machine,
we'll create a virtual enviroment and install the packages there

* to create a virtual enviroment run


    ``` virtualenv -p python3 venv```
* activating the enviroment

    ``` source venv/bin/activate```

The virtual enviroment is now ready, we can install all packages needed for project
ensure you have pip installed otherwise
then on your terminal run

``` pip install -r requirements.txt ```

# run
To test our project on your terminal run

``` export FLASK_APP=run.py```

then

``` flask run ```

# Run tests using nosetests

Install nosetest, codecov and coverage:

 ```pip install nose```
 ```pip install coverage```
 ```pip install codecov```

Within the root repository directory run the tests using nosetest with codecov for coverage:
 ```nosetests --with-coverage --cover-package=app/```

 # **Built with**
```
Python 3
Flask 1.0.2
nosetests
```