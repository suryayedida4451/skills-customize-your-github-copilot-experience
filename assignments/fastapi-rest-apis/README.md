# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API using FastAPI by defining routes, handling HTTP methods, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create API endpoints

#### Description
Use FastAPI to define a web API and create endpoints that return JSON data for both collection and single-item requests.

#### Requirements
Completed program should:

- Create a `FastAPI()` application instance.
- Define at least two `GET` endpoints.
- Return JSON objects from each endpoint.
- Use path parameters and query parameters in one endpoint.
- Provide clear route names for each endpoint.

Example response:

```json
{
  "item_id": 1,
  "name": "Sample Item",
  "available": true
}
```


### 🛠️ Add POST data handling and validation

#### Description
Add a `POST` endpoint that accepts JSON request data, validates it with Pydantic, and returns the created resource.

#### Requirements
Completed program should:

- Define a Pydantic model for the request body.
- Add a `POST` endpoint that accepts JSON payloads.
- Validate required fields and return a structured response.
- Return a `201` status code for successful creation.
- Include meaningful error responses for invalid input.
