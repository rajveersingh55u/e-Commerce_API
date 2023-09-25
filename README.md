# e-Commerce_API

LIVE:https://cute-gray-cormorant-coat.cyclic.cloud



eCommerceAPI is a RESTful API built with Node.js, Express, and MongoDB. It provides the backend functionality for an eCommerce web application, allowing admin to create products, update their quantity, browse and delete them.

Installation To install CSV_Upload, please follow these steps:

Clone this repository using the following command:



Install the required dependencies using the following command:

$ npm install Start the application using the following command:

$ npm start Open POSTMAN on this port, and follow the command in the features section:

$ http://localhost:8000 Features To create a product -> POST: http://localhost:8000/products/create To view all products -> GET: http://localhost:8000/products To update a product's quantity -> POST: http://localhost:8000/products/id/quant?quantity=value (id represents the id of the product, value is the desired quantity) To delete a product -> DELETE: http://localhost:8000//products/:id Folder Structure eCommerceAPI
| |--->config---->|--->mongoose.js |
| |-->home_controller.js |--->controllers-->|
| |-->product_controller.js |
|--->models---->|-->product.js |
| |-->index.js |--->routes---->| | |-->product.js |
| |-->node_modules |-->.gitignore |--> index.js |--> package-lock.json |-->package.json
