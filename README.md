<h1 align="center">Udaciracer Simulation Game :red_car:</h1>
<p>
  <img src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/wanderindev/udaciracer-simulator/blob/master/README.md">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/wanderindev/udaciracer-simulator/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/wanderindev/udaciracer-simulator/blob/master/LICENSE.md">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://twitter.com/JavierFeliuA">
    <img alt="Twitter: JavierFeliuA" src="https://img.shields.io/twitter/follow/JavierFeliuA.svg?style=social" target="_blank" />
  </a>
</p>

>Udaciracer Simulator Game is the third project for the Intemediate JavaScript Nanodegree. This
> project gives the student the opportunity to apply what was learned in the Asynchronous JavaScript course.

## Project overview
You can find the starter code for the project [here](https://github.com/udacity/nd032-c3-asynchronous-programming-with-javascript-project-starter).

The purpose of the project is to create a race simulation game using asynchronous JavaScript.  Udacity provided much of the code.  My task
was to complete all TODOs in `.client/assets/javascript/index.js`.

## How to use

### Clone the repository
If you want to use the code, you can clone the repository:
```sh
git clone https://github.com/wanderindev/udaciracer-simulator.git
cd udaciracer-simulator
``` 

### Start the server
The game engine has been compiled down to a binary so that you can run it on any system. Because of this, you cannot 
edit the API in any way, it is just a black box that we interact with via the API endpoints.

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project 
root to start the front end.

#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json
2. Run the following command to add the environment variable: ```set DATA_FILE=./data.json```

### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. 
Then you should be able to access http://localhost:3000.

## Author

👤 **Javier Feliu**

* Twitter: [@JavierFeliuA](https://twitter.com/JavierFeliuA)
* Github: [@wanderindev](https://github.com/wanderindev)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2021 [Javier Feliu](https://github.com/wanderindev).<br />

This project is [MIT](https://github.com/wanderindev/udaciracer-simulator/blob/master/LICENSE.md) licensed.

***
_I based this README on a template generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_