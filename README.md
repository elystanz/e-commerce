# E-Commerce Back End
# Table of Contents
1. [Introduction](#introduction)
2. [Application](#application)
3. [Roadmap](#roadmap)
4. [Contributions](#contributions)
5. [Authors](#authors)
6. [License](#license)


## <a id="introduction">Introduction</a>
E-Commerce Back End is the perfect starting point for your new store. Use this back end to jump-start your business and keep track of your inventory, pricing, and organizational habits!

Once you've cloned the repository, open your terminal and enter `npm i` to install all required dependencies. Ensure your credentials are in correctly within the env file for the MySQL database -- you may need to enter your password.

Navigate back to your terminal and enter `mysql -u root -p` to enter the MySQL database. Type `source db/schema.sql` to engage the SQL database, `quit` MySQL, and `node index.js` into the application!

## <a id="application">Application</a>
Here is the application in use:

### Categories
![CATEGORIESdemo](https://user-images.githubusercontent.com/95983252/179428430-daafa809-d521-48cf-8770-cd7fe253a533.gif)

### Products
![PRODUCTSdemo](https://user-images.githubusercontent.com/95983252/179428433-de6567c0-9afc-4a8a-85b3-8f86465e3da3.gif)

### Tags
![TAGSdemo](https://user-images.githubusercontent.com/95983252/179428434-f8aa74a4-f20c-4fbf-bb41-28a689ad3a3e.gif)

This application requires the following dependencies to run, which are already declared within the package.json file:

* dotenv (^8.2.0)
* express (^4.17.1)
* mysql2 (^2.3.3)
* sequelize (^5.21.7)
* node-modules (^1.0.1)

## <a id="roadmap">Roadmap</a>
Currently there are no plans to expand this application. Bug fixes are coming, address in a later segment of this README. Suggestions are welcome!

## <a id="contributions">Contributions</a>
Please feel free to make a pull request or submit an issue to troubleshoot any bugs you come across.

## <a id="authors">Authors</a>
[Elyse Stanziale](https://github.com/elystanz) is the main contributors and the creators of this application.

## <a id="license">License</a>
This application is protected under the ISC license.

## <a id=#status>Project Status</a>
Currently when updating a product via Insomnia, the request comes back as a 400 but still goes through with the request and posts the updated product to the database, which can be seen in the Product demo video above.
