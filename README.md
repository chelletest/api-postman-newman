# api-postman-newman - sample2
# API Automation Sample with Postman & Newman

This is a basic API automation sample using Postman and Newman to test the **JSONPlaceholder** API.
Validating JSON structure, reponse headers, status codes and performance

##  Description

- This project contains a **Postman collection** that tests a **GET request** to the endpoint `https://jsonplaceholder.typicode.com/posts/1`.
- It includes tests for checking JSON structure, JSON values, validating response headers, verifying the status code, response time and body length.

##  Tools Used

- Postman (API testing)
- Newman (Postman’s CLI tool for automation)

##  How to Run

1. Install **Newman**:
    ```bash
    npm install -g newman
    ```
2. Run the collection:
    ```bash
    newman run api-tests.postman_collection1.json
    ```

##  Collection File

- **API Test Collection**: `api-tests.postman_collection1.json`

##  Licence   

This project is licenced under the MIT Licence.
---
