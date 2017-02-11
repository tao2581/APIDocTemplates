# Checkout flow 

## Quickstart 

The checkout flow adds products to a customer’s shopping cart, retrieves the cart contents, and moves them through the order and payment process. The checkout flow consists of four steps:  

1. Add a product to a cart   
2. Get cart contents   
3. Convert cart to an order  
4. Process payment  


This QuickStart will walk you through the API endpoints needed to complete the basic checkout process.

---

## Before you begin - authentication 

In order to send API requests, you will need a bearer token that is generated from your store keys, which are found in your [Accounts Management Dashboard](https://accounts.moltin.com/ "Accounts Management Dashboard"). You can retrieve your bearer token using `cURL`. 


```
curl -X POST https://api.moltin.com/oauth/access_token \ 
  -d "client_id=XXX" \
  -d "client_secret=XXX" \
  -d "grant_type=client_credentials"
  ```

--- 

## Step 1. Add a product to a cart
(what the endpoint actually does, like "Retrieve all user names")

Description (a description, such as "Retrieves all user names available in customer account")

### Endpoint

`resource/endpoint/{parameter}`

### Method and URL

`METHOD https://api.example.com/resource/endpoint/{parameter}`


### Query parameters

| Parameter   | Description     | Type     | Required     | Notes     |
|-------------|-----------------|----------|--------------|-----------|
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |


### Sample Request

`METHOD https://api.example.com/resource/endpoint/{parameter}`

`curl --get --include 'https://api.example.com/resource/endpoint/parameter`


### Sample Response

{
  "query": {
    "tool": "tool",
    "domain": "example.com"
  },
    "response": {
      "parameter": "parameter response"
  }
}



| Element     |   Description   |   Type   |   Notes   |
|-------------|-----------------|----------|-----------|
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |


## Step 2. Get cart contents
(what the endpoint actually does, like "Retrieve all user names")

Description (a description, such as "Retrieves all user names available in customer account")

### Endpoint

`resource/endpoint/{parameter}`

### Method and URL

`METHOD https://api.example.com/resource/endpoint/{parameter}`


### Query parameters

| Parameter   | Description     | Type     | Required     | Notes     |
|-------------|-----------------|----------|--------------|-----------|
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |


### Sample Request

`METHOD https://api.example.com/resource/endpoint/{parameter}`

`curl --get --include 'https://api.example.com/resource/endpoint/parameter`


### Sample Response

{
  "query": {
    "tool": "tool",
    "domain": "example.com"
  },
    "response": {
      "parameter": "parameter response"
  }
}



| Element     |   Description   |   Type   |   Notes   |
|-------------|-----------------|----------|-----------|
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |

## Step 3. Convert cart to an order 
(what the endpoint actually does, like "Retrieve all user names")

Description (a description, such as "Retrieves all user names available in customer account")

### Endpoint

`resource/endpoint/{parameter}`

### Method and URL

`METHOD https://api.example.com/resource/endpoint/{parameter}`


### Query parameters

| Parameter   | Description     | Type     | Required     | Notes     |
|-------------|-----------------|----------|--------------|-----------|
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |


### Sample Request

`METHOD https://api.example.com/resource/endpoint/{parameter}`

`curl --get --include 'https://api.example.com/resource/endpoint/parameter`


### Sample Response

{
  "query": {
    "tool": "tool",
    "domain": "example.com"
  },
    "response": {
      "parameter": "parameter response"
  }
}



| Element     |   Description   |   Type   |   Notes   |
|-------------|-----------------|----------|-----------|
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |


## Step 4. Process payment
(what the endpoint actually does, like "Retrieve all user names")

Description (a description, such as "Retrieves all user names available in customer account")

### Endpoint

`resource/endpoint/{parameter}`

### Method and URL

`METHOD https://api.example.com/resource/endpoint/{parameter}`


### Query parameters

| Parameter   | Description     | Type     | Required     | Notes     |
|-------------|-----------------|----------|--------------|-----------|
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |
|  **Value**  |    Value        |  Value   |  Value       | Value     |


### Sample Request

`METHOD https://api.example.com/resource/endpoint/{parameter}`

`curl --get --include 'https://api.example.com/resource/endpoint/parameter`


### Sample Response

{
  "query": {
    "tool": "tool",
    "domain": "example.com"
  },
    "response": {
      "parameter": "parameter response"
  }
}



| Element     |   Description   |   Type   |   Notes   |
|-------------|-----------------|----------|-----------|
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |
|  **Value**  |    Value        |  Value   |  Value    |

---

### Status Codes and Errors

|     Code    | Description     |  Notes       |
|-------------|-----------------|--------------|
|  **Value**  |    Value        |  Value       |
|  **Value**  |    Value        |  Value       |
|  **Value**  |    Value        |  Value       |