# Microservice Product

### Endpoints:

#### Save Product 

````
POST /api/product HTTP/1.1
Host: localhost:3333
Content-Type: application/json
Content-Length: 46

{
    "name": "test-1",
    "price": 13.4
}

````

#### Get Products

````
GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:password)

````


#### Delete Product

````
DELETE /api/product/1 HTTP/1.1
Host: localhost:3333
Content-Type: application/json
Content-Length: 46

{
    "name": "test-1",
    "price": 13.4
}

````