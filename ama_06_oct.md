# AMA - 06 Oct

## 1. What happens when a view function does not return anything?

A view must return an HTTP response. If it returns nothing, Django raises an error.

## 2. What is a `Q` expression in Django?

`Q` expressions are used to build complex database queries using conditions like `AND` and `OR`.

## 3. What is AJAX?

AJAX allows a web page to send and receive data from the server without reloading the whole page.

## 4. How do we validate a password in Django?

We can use Django's `authenticate()` function to check whether the username and password are valid.

## 5. What is `SECRET_KEY`?

`SECRET_KEY` is a private Django setting used for security and cryptographic operations.

## 6. What is `settings.py`?

`settings.py` contains the main configuration settings of a Django project.

## 7. How does your project work?

The user sends a request, Django's URL routes it to a view, the view uses models/ORM if needed, and returns a response through a template or API.

## 8. What is the `slugify()` function in Django?

`slugify()` converts text into a URL-friendly format, such as `Hello World` → `hello-world`.

## 9. What is ORM?

ORM (Object-Relational Mapping) allows us to work with database tables using Python objects and Django models instead of writing SQL directly.

## 10. What is the status code for an unauthorized user?

`401 Unauthorized`.
