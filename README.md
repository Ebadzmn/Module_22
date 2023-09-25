Module 22 Assignment

In this assignment, you have to create a project structure with express.js. Create your folders and files with the following structure.

1. Package.json is mandatory

2. config.env is mandatory. There will be a variable named RUNNING_PORT. This variable should be used in your application.

3. You need to download some important MPM packages, they are: express, body-parser, cookie-parser, multer, jsonwebtoken, mysql, mongoose, dotenv, cors, express-mongo-sanitize, express-rate-limit, helmet, hpp, validator, nodemon

4. Index.js should be mandatory. where your application will run. And listen port must be 8080.

5. App.js is mandatory. where the configuration will hold. All security middleware must be used here.

6. An undefined route must be created where the response will have 404 status code.

7. Make sure that node_modules and config.env files are not uploaded to Git.

8. There should be a src folder. There will be five folders inside the folder Controllers, Helper, Middleware, Models, and Routes.

9. There will be a total of 13 Controller files inside the Controllers folder. In order they are - userController.js, adminController.js, subAdminController.js, postController.js, customerController.js, categoryController.js, orderController.js, productController.js, order_itemController.js, paymentController.js, shipmentController.js, cartController.js, wishlistController.js

10. Each controller will have four function exports. They are respectively - create, read, delete, and update.

For example :

exports.create = async (req, res) => { };

exports.read = async (req, res) => { };

exports.delete = async (req, res) => { };

exports.update = async (req, res) => { };

11. Each function of the controller should use res.status().json() method to pass some information. For example: res.status(200).json({status:“success”, data: “Can contain any information”})

12. The Routes folder will contain the api.js file. And router path should be created in this file. Since there will be 13 controller files and each file will have 4 functions, a total of 52 router paths will be created. All APIs must be made through GET request.

13. The Helper, Middleware, and Models folders will contain a file called demo.txt.

14. Create a database in mongodb and add it to your application. And provide some information to the console to check if it is connected.

Submit Instruction:

Once the project structure is created, you upload the project to GitHub and submit the GitHub repository link.
