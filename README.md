# IBM DevOps certification
## Introduction to Test Driven Development - Week 2
### Methods for Test Driven Development

# Hands-on Lab: Running tests with Nose

1. Clone the Git repository

git clone <https://github.com/ibm-developer-skills-network/duwjx-tdd_bdd_PracticeCode.git>

* change the directory to 

$ cd duwjx-tdd_bdd_PracticeCode

$ cd labs/01_running_tests_with_nose/

$ ls -l

2. Working with unittest

$ python3 -m unittest

3. Display a more verbose output

$ python3 -m unittest -v

## Working with Nose

1. Install nose

$ pip install nose

2. To see verbose output from nose

$ nosetests -v

## Adding color with Pinocchio

1. install pinocchio

$ pip install pinocchio

2. to get nicerr formatting and colorful output 

$ nosetests --with-spec --spec-color
## Adding test coverage

1. install coverage

$ pip install coverage

2. Call coverage through nose

$ nosetests --with-spec --spec-color --with-coverage
## Create missing coverage report

$ coverage report -m

## Automate the testing

1. Create a setup.cfg file in labs/01_running_test_with_nose

2. Run the nosetest with config

$ nosetests
