# API Automation Testing Project

This repository contains an automated testing suite for a REST API, developed using **Postman**.

##Project Overview
The goal of this project was to transition from manual testing to automation by creating a regression test suite for a sample blog API.

##Tools Used 

* **Postman**: For request building and collection management.
* **JavaScript**: For writing automated validation scripts (Post-response scripts).

##Tests Included

1. **GET Requests**:
  - Validated '200 OK' status codes.
  - Verified that the response body contains the correct data(ID, Title).
2. **POST Requests**:
  - Validated '201 Created' status codes.
  - Checked if the resource was successfully simulated on the server.
 
