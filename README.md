# Zodiac Todo Example

An example todo web app using [Zodiac](https://github.com/brettatoms/zodiac), [Zodiac Assets](https://github.com/brettatoms/zodiac-assets) and [Zodiac SQL](https://github.com/brettatoms/zodiac-sql).

The intention of this example is to show how it's possible to create a simple interactive web app using Zodiac and its extensions with very little code.  The application code here is < 200 lines but still supports client side interactivity, updates without full page reloads, CSRF token handling, flash messages, using standard HTTP requests and responses and very little magic.

This is a toy app.  There is still a lot of things missing like error handling, authentication, etc.

On the client side we're using [Tailwind]() for styling, [AlpineJS]() for client side interactivity and [Htmx]() for making request and updating the UI with the response.

On the server side we use an in memory [SQLite]() database to store the todo items.

## Getting Started

You will need to install the following dependencies to run the app:
- Clojure
- Node.js

### Run the app
```sh
clojure -M:main
```
