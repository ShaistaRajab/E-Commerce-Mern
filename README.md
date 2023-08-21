EXPRESS API link here 
https://github.com/ShaistaRajab/express-


API### GET ALL PRODUCTS
GET http://localhost:8080/api/products HTTP/1.1

### GET SINGLE PRODUCT
GET http://localhost:8080/api/products/60e0102521438724ac4638f4 HTTP/1.1

### ADD ITEM
POST http://localhost:8080/api/products HTTP/1.1
Content-Type: application/json



### DELETE ITEM
DELETE http://localhost:8080/api/products/60e00f8e21438724ac4638ef HTTP/1.1

### UPDATE ITEM
PUT http://localhost:8080/api/products/60e00f8e21438724ac4638ef HTTP/1.1
Content-Type: application/json

{
  "title": "Updated product title"
}
