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

# Hand-on Lab: Writing Test Assertions

## Setup the Lab Environment

1. Clone the code repo

$ git clone <https://github.com/ibm-developer-skills-network/duwjx-tdd_bdd_PracticeCode.git>

2. change into the lab folder

$ cd duwjx-tdd_bdd_PracticeCode/labs/02_writing_test_assertions/

$ ls -l

3. Install the requirments

$ pip install -r requirements.txt

4. Optional: shorten the command prompt:

$ export PS1="[\[\033[01;32m\]\u\[\033[00m\]: \[\033[01;34m\]\W\[\033[00m\]]\$ "

## Working with the test files
1. Review test_stack.py and stack.py

## Running nosetest

$ nosetests

## Finding the first Error

$ nosetests --stop

1. Testing the is_empty() method

2. Testing the peek() method
3. Testing the pop() method
4. Testing the push() method

# Hands-On Lab: Creating an Initial State Using Test Fixtures

## Set up the lab Environment

1. Clone the code repo

$ git clone <https://github.com/ibm-developer-skills-network/duwjx-tdd_bdd_PracticeCode.git>

$
cd duwjx-tdd_bdd_PracticeCode/labs/03_test_fixtures

$ pip install -r requirements.txt

* optional:

$ export PS1="[\[\033[01;32m\]\u\[\033[00m\]: \[\033[01;34m\]\W\[\033[00m\]]\$ "

1. Initialize the database at test_account.py

* run the test $ nosetests

2. Load test data into a global variable called ACCOUNT_DATA in tests/fixtures/account_data.json

3. Write a test case to create an account

4. Write a test case to create all accounts
5. Clear out the tables before each test
