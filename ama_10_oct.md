# AMA - 10 Oct

## 1. What does the migration command do in Django?

`migrate` applies migration files to the database and updates its structure.

## 2. What is the difference between a foreign key and a join?

A foreign key links records between tables. A join combines related data from tables in a query.

## 3. How do you implement static files in Django?

Add `django.contrib.staticfiles` to `INSTALLED_APPS`, configure `STATIC_URL`, and use `{% load static %}` with `{% static 'path/to/file' %}` in templates.

## 4. What is a candidate key?

A candidate key is a column or set of columns that uniquely identifies each row in a table.

## 5. What are the array methods in Python?

Python lists provide methods such as `append()`, `extend()`, `insert()`, `remove()`, `pop()`, `sort()`, and `reverse()`.

## 6. What is `SECRET_KEY` in Django?

`SECRET_KEY` is a private setting used by Django for security-related cryptographic operations.

## 7. What is the difference between `GROUP BY` and `ORDER BY` in SQL?

`GROUP BY` groups rows with matching values. `ORDER BY` sorts the query results.

## 8. What is the DOM?

The DOM (Document Object Model) represents an HTML page as a tree of objects that JavaScript can access and change.

## 9. What is a QuerySet?

A QuerySet is a collection of database records returned by a Django query.

## 10. What is template inheritance?

Template inheritance lets a child template reuse a base template and override specific sections.
