# Postman API Tests – JSONPlaceholder

This repository contains API tests written in Postman for the JSONPlaceholder fake REST API.

## API
https://jsonplaceholder.typicode.com

## Running tests (optional)

This Postman collection can be executed from the command line using **Newman**.

Install Newman:
```bash
npm install -g newman

Run:

newman run postman/jsonplaceholder.postman_collection.json \
  -e postman/jsonplaceholder.postman_environment.json

Mock API disclaimer

This project uses JSONPlaceholder, which is a mock REST API.

    POST, PUT, PATCH, and DELETE requests are simulated

    Data is not persisted

    GET requests always return the original, static data

    Responses may not reflect real backend behavior

The purpose of this project is to demonstrate:

    API testing in Postman

    Request validation

    Status code and response structure checks

    Handling of mock APIs and simulated write operations

Notes

    When using POST, new IDs are returned but do not actually exist on the server.

    PUT/PATCH requests to non-existent IDs (like 101) may fail (500 error) because JSONPlaceholder only has static resources 1–100.

    This README ensures clarity about the behavior of the mock API for anyone running or reviewing these tests.
