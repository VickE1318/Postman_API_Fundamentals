# E-Commerce API Testing Framework

## Overview

API automation framework built using Postman and Newman.

## Modules Covered

### Authentication
- Valid Login
- Invalid Password
- Empty Credentials

### Products
- Get Products
- Product Data Validation
- Single Product Retrieval
- Invalid Product ID

### Cart
- Add Cart
- Invalid Product
- Invalid Quantity
- Invalid User

## Tools Used

- Postman
- Newman
- JavaScript
- REST API
- GitHub

## Run Tests via CLI

```bash
npm install newman
npm install newman-reporter-htmlextra
npx newman run ".\collections\API_Testing-E-Commerce_APIs.postman_collection.json" -e ".\environments\E-Commerce-Environment.postman_environment.json" -r htmlextra --reporter-htmlextra-export ".\reports\report.html"
```

## Run Tests via GUI

- Install postman in your machine.
- Open the postman and import this collection and environment.
- In Collection tab, click on RUN.
