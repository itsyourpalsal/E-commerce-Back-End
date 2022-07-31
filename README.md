<h1 align="center">Welcome to my E-commerce Application👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/Brainybrian316/E-commerce-Back-End/blob/main/README.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/Brainybrian316/E-commerce-Back-End/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
  <a href="https://opensource.org/licenses/MIT" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-ISC-GREEN.svg" />
  </a>
</p>

> A backend development application that creates a database for an e-commerce site that will utilize Object-Relational Mapping to interact with the database. The application is built using best practices from the RESTful CRUD operations concept. This is a command line application to manage an e-commerce database site using MySQL, which utilizes Node.js, MySQL2, Express.js, Nodemon, and Sequelize.


***
## Demo of Project 

### 🏠 [Homepage](https://github.com/Brainybrian316/E-commerce-Back-End)
### ✨ [Live Demo](https://user-images.githubusercontent.com/99369106/168486014-38a9bed0-3895-4878-ac5e-f79cf1449982.mp4)

***
## Install
To install all dependencies you need only to run:
```sh
npm install
```
However, if you plan on editing data you may find it helpful to install Nodemon running: 
```
npm install --save-dev nodemon
```
Please review <a href ="https://www.npmjs.com/package/nodemon">Nodemon</a> documentation if you are unfamiliar with the package.

***
## Usage
Run the following command at the root of your project starting with:
```
mysql -u root -p
``` 
Next, enter your password for MySQL. Once you are in your server run: 
```
SOURCE db/schema.sql
quit
``` 
Then run:
```
npm run seed
```
Finally, choose between running: 
```
nodemon server.js
OR
npm start
```
You can download <a href="https://insomnia.rest/download">Insomnia</a> to manipulate/test the data with the GET, POST, PUT, DELETE request.

***
## Author

👤 **Brainybrian316**

* Website: https://brainybrian316.com/
* Github: [@Brainybrian316](https://github.com/Brainybrian316)
* LinkedIn: [@brainybrian316](https://linkedin.com/in/brainybrian316)
***

## 🤝 Contributing


Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/Brainybrian316/E-commerce-Back-End/issues). You can also take a look at the contributing guide below: 
&nbsp;

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project

2. Create your Feature Branch (git checkout -b feature/AmazingFeature)

3. Commit your Changes (git commit -m 'Add some AmazingFeature')

4. Push to the Branch (git push origin feature/AmazingFeature)

5. Open a Pull Request

***
## Show your support


<p> Give a ⭐️ if this project helped you! </p>
<p> Buy me a coffee by becoming a patreon ☕️ </p>

<a href="https://www.patreon.com/brainybrian316">
  <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

***
## 📝 License

Copyright © 2022 [Brainybrian316](https://github.com/Brainybrian316).<br />
This project is [ISC](https://opensource.org/licenses/MIT) licensed.

***