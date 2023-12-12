# restaurants-with-sqlalchemy
# SQLAlchemy-Code-Challenge-Restaurants
## Author
Ian Were

## Introduction

This repo contains code for a restaurant review system for restuarants-code-challenge-sqlalchemy based on python classes and instances, class and instance methods, variable scope, object relationships, and lists and list methods working with  sqlalchemy.

This project utilizes the `pytest` library for testing purposes. The `pytest framework` makes it easy to write small, readable tests, and can scale to support complex functional testing for applications and libraries.


## Table of Contents
* Technologies used
* Installation
* Usage
* Author

## Technologies used
* Python
* SQLAlchemy
* Faker
* Alembic

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/faith-kaburu/restaurants-with-sqlalchemy.git
```

### 2. Navigate to the project's directory

```bash
cd  restaurants-with-sqlalchemy
```

### 3. Install all the required dependencies

The root directory of this repository contains the `Pipfile` with all the required Python libraries for this project and restricts them to this repository.

To install `pytest` and any other required libraries, run:

```python
pipenv install
```

### 4. Enter the pipenv shell

```python
pipenv shell
```


## Usage

* Website contains tables for restaurants reviews and customers.
* The methods for the restaurant,reviews and customers models are in the `models.py` file.
* To test the methods enter into the pipenv shell and ensure that you are in `lib` directory then run `python3 debug.py`.
