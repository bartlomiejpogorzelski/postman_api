# Postman API Tests – JSONPlaceholder

API tests written in Postman for the JSONPlaceholder fake REST API.

## API
https://jsonplaceholder.typicode.com

## Running tests (optional)

This Postman collection can be executed from the command line using **Newman**.
Install Newman:
```bash
npm install -g newman

```bash
newman run postman/jsonplaceholder.postman_collection.json \
  -e postman/jsonplaceholder.postman_environment.json



## Mock API disclaimer

This project uses **JSONPlaceholder**, which is a **mock REST API**.

- POST, PUT, PATCH and DELETE requests are **simulated**
- Data is **not persisted**
- Responses may not reflect real backend behavior

The purpose of this project is to demonstrate:
- API testing in Postman
- Request validation
- Status code and response structure checks
