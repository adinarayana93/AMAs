# AMA - 21 Sep

## How do you connect to an SQL database?

Use the database's connection method with the required host, username, password, and database name.

```bash
psql -h hostname -U username -d database_name
```

## What is the DOM?

DOM (Document Object Model) is a tree-like representation of an HTML document that JavaScript can access and modify.

## How do you connect JavaScript code inside HTML?

Use the `<script>` tag.

```html
<script src="fileName.js"></script>
```

## What is the `document` object in JavaScript?

The `document` object represents the current HTML page and lets JavaScript access and modify its elements.

## What are the different ways to write CSS?

- Inline CSS
- Internal CSS
- External CSS

## What are the states of promises?

- Pending
- Fulfilled
- Rejected

## What is abstraction?

Abstraction means hiding unnecessary implementation details and showing only the important parts.

## What is the difference between `rest` and `spread` in JavaScript?

- `Rest` collects multiple values into one array.
- `Spread` expands an array or object into individual values.

## What is the difference between `.then()` and `.catch()`?

- `.then()` handles a successful Promise result.
- `.catch()` handles a rejected Promise or error.

## What is the difference between `getElementById()` and `querySelector()`?

- `getElementById()` selects an element using its ID.
- `querySelector()` selects the first element matching a CSS selector.

## What is `await`?

`await` pauses an `async` function until a Promise settles and gives its result.

## What is `async`?

`async` makes a function return a Promise and allows the use of `await` inside it.

## What is the need for `package.json`?

`package.json` stores project information, dependencies, scripts, and other Node.js project configuration.
