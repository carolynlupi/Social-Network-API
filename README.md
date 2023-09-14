# Social-Network-API

Week-18 Challenge (MongoDB)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Table of Contents

- [Description](#description)

- [Youtube Link](#youtube-link)

- [Screenshots](#screenshots)

- [Technologies-Used](#technologies-used)

- [Installation](#installation)

- [Usage-Information](#usage-information)

- [License](#license)

- [Questions & Credits](#questions)

## Description

This application marks the initial phase of a comprehensive full-stack social networking project utilizing a MongoDB database, Express.js for routing, and the Mongoose ODM (Object Data Modeling). It lays the groundwork for essential CRUD (Create, Read, Update, Delete) API routes within the application. These routes enable users to be created, searched, updated, and removed. Additionally, users can engage in various activities, such as sharing thoughts, reacting to friends' thoughts, building a friend list, and subsequently deleting thoughts, reactions, friends, or even their own user profile.

While this application is just scratching the surface of its full potential, it plays a crucial role in understanding the capabilities of MongoDB and the Mongoose ODM. One of the primary challenges encountered during its development was navigating the intricacies of MongoDB's more flexible data querying and insertion processes compared to SQL databases. Additionally, troubleshooting became trickier due to the subtlety of errors. Another hurdle was optimizing the deletion of data in a cascading manner and handling table joins, which presented unique challenges in a MongoDB environment.

Despite these challenges, this project has expanded my knowledge of full-stack development, adding another potent tool to my arsenal within the MERN (MongoDB, Express.js, React, Node.js) stack. Moving forward, I intend to enhance this application's functionality by building a robust front-end UI with React, transforming it into a complete MERN-based full-stack application.

## Youtube Link

https://www.youtube.com/watch?v=srYPAU4dZ9g&ab_channel=Carolyn

## Screenshots

## Technologies Used

This application is powered by Node.js (v16.19.1), Express.js (v.14.18.2), JavaScript, MongoDB, and Mongoose (ODM). It utilizes the node package manager (npm) dependencies express (v4.18.2), and mongoose (v7.2.2). Nodemon (v2.0.22) was utilized as a devDependency allowing the server to refresh when edits were made to application. Jest (v.29.5.0) is installed as a devDependency for future unit testing. MongoDB Compass acted as the interactive shell used to visually see the database. Also, the Insomnia application, was utilized to test the functionality of routes within the program.

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

## Installation

1. Clone the repo:
   git clone this repo

2. Open in VS Code. 

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16).

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install dependencies directly from the command line).

   Commands to install each dependency:
   - Command for express will be npm i express@4.18.2
   - Command for mongoose will be npm i mongoose
   - Command for nodemon will be npm i nodemon
   - Command for jest will be npm i jest

6. Next, you will want to make sure you have access to a MongoDB account and MongoDB Compass, these will allow you to interact with the database and visually confirm what changes are being made in the database. (Link for MongoDB & MongoDB Compass download -> https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb).

7. Once all dependencies are installed, you will then be able to run the command npm start from the root directory to spin up the server. With nodemon installed, you will also be able to utilize the command npm run dev to keep the server spun up between code edits.

8. From there, you can utilize applications such as Insomnia to test the functionality of the API routes within the program and make edits to the code base (Link to install Insomnia -> https://docs.insomnia.rest/insomnia/install).

## Usage Information

As of now the usage of this application can be conducted through spinning up the server with npm run start or nodemon with npm run dev, then heading over to an application like Insomnia or Postman and testing different API end points. For further information on starting up the server, MongoDB Compass and MongoDB installation navigate to the Installation section above.

## Contribution Guidelines

Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.

## Test Instructions

There is currently no unit testing written yet for this application.

## License

NOTICE: This application is covered under the MIT License

## Questions &b Credits

[Link to Github](https://github.com/carolynlupi)
