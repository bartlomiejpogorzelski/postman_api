````md
# Postman API Tests – JSONPlaceholder

This repository contains API tests written in **Postman** for the JSONPlaceholder fake REST API (`https://jsonplaceholder.typicode.com`).  
Tests cover basic CRUD scenarios, response validation, and behavior specific to mock APIs.

## Run the tests

Optionally, the collection can be executed from the command line using **Newman**:

```bash
npm install -g newman
newman run postman/jsonplaceholder.postman_collection.json \
  -e postman/jsonplaceholder.postman_environment.json
````

## Mock API Disclaimer

JSONPlaceholder is a **mock REST API**.
POST, PUT, PATCH, and DELETE requests are **simulated**, data is **not persisted**, and GET requests always return static data.
Newly created IDs (e.g. `101`) do not actually exist on the server, and write operations may behave differently than on a real backend.
The purpose of this project is to demonstrate API testing in Postman, request/response validation, status code checks, and handling of mock APIs.

```
```
