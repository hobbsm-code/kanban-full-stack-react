# README  
  ## License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  https://opensource.org/licenses/MIT  
    This project is licensed under the MIT license. 
    Click the badge for more information.  
  ## Description  
    This application is a full-stack Kanban board that allows users to create, update, and delete tasks. The application is built using React, Node.js, Express, and PostgreSQL. 

  ## Table of Contents  
  - [Description](#description)  
  - [Installation](#installation)  
  - [Usage](#usage)  
  - [License](#license)  
  - [Contribution](#contribution)  
  - [Tests](#tests)  
  - [Questions](#questions)  
  ## Installation  
  To install this project:  

  1. Clone the repo
   ```sh
    git@github.com:hobbsm-code/kanban-full-stack-react.git
   ```
  2. Install NPM packages (from the Develop directory)
   ```sh
   npm run install
   ```

  ## Usage  
  Please follow these instructions to use the Kanban board application:

  1. Open a terminal and cd into the Develop directory 
  2. Type npm run install to install the node modules for the client and server packages.
  3. Type npm run start:dev to run the application in development mode or npm run start to run the application in production mode
  3. The application will open in your default browser and you will see the Login page*
  4. Default users can be found in server/src/seeds/user-seeds.ts file.

  *Note: In order to use this application, a local PostgreSQL installation is required. Also, the user must create a file called .env, save it in the server directory, include the following environment variables: 
  DB_NAME='kanban_db'
  DB_USER=[your db user name]
  DB_PASSWORD=[your db password]
  JWT_SECRET_KEY=[a secret key that can be any string]
  
  ## Contribution  
  Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

  If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
  Don't forget to give the project a star! Thanks again!

  1. Fork the Project
  2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
  3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
  4. Push to the Branch (`git push origin feature/AmazingFeature`)
  5. Open a Pull Request

  ## Tests  
  Test instructions:  

  This project does not currently have any unit tests. Having test coverage is always welcome. Please feel free to contribute some unit tests. Otherwise, it is our goal to improve the test coverage as the project becomes more mature and more complex functionality is added.

  ## Questions  
  For questions, please contact me at:  
  GitHub: [Find me on GitHub ->  hobbsm-code](https://github.com/Find me on GitHub ->  hobbsm-code)  
  Email: [Email me at: hobbsm321@gmail.com]  
  
