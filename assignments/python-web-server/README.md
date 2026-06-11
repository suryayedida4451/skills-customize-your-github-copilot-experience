# 📘 Assignment: Simple Python Web Server

## 🎯 Objective

Learn how HTTP request handling works by building a basic Python web server that responds with HTML and JSON without using external web frameworks.

## 📝 Tasks

### 🛠️ Build a basic web server

#### Description
Use Python's built-in `http.server` module to create a web server that listens for incoming requests and returns a simple HTML page.

#### Requirements
Completed program should:

- Use `http.server` and `socketserver` from the Python standard library.
- Serve an HTML page at the root path `/`.
- Include a page title and heading in the response HTML.
- Start the server on a local port such as `8000`.


### 🛠️ Add a JSON API endpoint

#### Description
Create a second route that returns structured JSON data when a client requests a specific path.

#### Requirements
Completed program should:

- Return JSON from a route such as `/api/status`.
- Set the correct `Content-Type` header for JSON responses.
- Include at least two fields in the JSON response (for example, `status` and `message`).
- Support at least one route that uses a path segment or query parameter.
