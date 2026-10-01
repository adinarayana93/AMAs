# AMA - 01 Oct

## In which files do `makemigrations` and `migrate` make changes?

`makemigrations` creates migration files inside the app's `migrations/` folder. `migrate` applies those migrations to the database.

## What is `Promise.race()`?

`Promise.race()` settles with the result or error of the first Promise that settles.

## What is `SECRET_KEY`?

`SECRET_KEY` is a private Django setting used for cryptographic signing and security-related features.

## What is `<!DOCTYPE html>`?

It tells the browser to render the page using modern HTML standards mode.

## What is `manage.py`?

`manage.py` is a Django command-line utility used to run project commands, such as `runserver` and `migrate`.

## What is a model class?

A model class defines a database table's structure and the data it stores in Django.

## What is multiple inheritance?

Multiple inheritance means a class inherits attributes and methods from more than one parent class.

## What is ORM?

ORM (Object-Relational Mapping) lets us work with database records using objects and code instead of writing SQL for every operation.

## What is the difference between `kill -9` and `kill -15`?

- `kill -15` asks a process to stop gracefully.
- `kill -9` forces the process to stop immediately.

## How do you identify a class and a module in Django?

A class is defined using the `class` keyword in a Python file. A module is a Python file, such as `models.py` or `views.py`.
