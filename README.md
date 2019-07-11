# LAB - 06

## Simple-API

### Author: 401n13 Students

### Links and Resources
* [submission PR](https://github.com/401-advanced-javascriptnights-joseph/simple-api/pull/1)

#### Documentation
* [api docs](https://app.swaggerhub.com/apis/JCode1986/simple-api/0.1)

### Modules
#### `db.json` - file with categories and products
#### `swagger.json` - file with categories and products

#### `.env` requirements
* `local host` - 3000

#### Running the app
* `npm start`
* Endpoint: /categories GET, POST
* Endpoint: /categories/:id/ PUT, DELETE
* Endpoint: /products GET, POST
* Endpoint: /products/:id/ PUT, DELETE
* Example inputs in CLI
* GET
  * http get http://localhost:3000/categories/1
* POST (create)
  * echo '{"id": 1, "description":"value","display_name": "value", "name":"value"}' | http post :3000/categories
* PUT (update)
  * echo '{"id": 1, "description":"value","display_name": "value", "name":"value"}' | http put :3000/categories
* DELETE
  * http delete http://localhost:3000/categories/1

#### UML
![UML](./images/UML.jpg)
