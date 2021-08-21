# PWA-Budget-Tracker
Deployed Link: https://kc-budget-tracker.herokuapp.com

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This project allows users to track their budget. Users can add and subtract their spendings and the database and cache will rememter the data that user input. When user comes back to the budget tracker application, they will be able to check their budget records. In this project, PWA was implemented. PWA allows user to install the website as an application and user can still access to the application while offline. While the application is offline, the data will stay stand-by and then will be added to database once it is back to online. The demonstration will be shown in following sections.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
 
  ## Installation
  Fork this repo into your GitHub. Make sure the fork process has been completed without any issue by checking all files in your forked repo. Verify whether you have node.js installed on your desktop or not by running the command `node -v` in your terminal. If you do not have node.js installed, please go to [https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs](https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs) and it will walk you through the process.

  You also need `MongoDB` in order to run this application. If you do not have `MongoDB` installed on your device, then please install.

  Once you completed the installation process, make sure your MongoDB is running. Then, try to run `npm start`, it will probably give you an error BECAUSE the required dependencies are not installed yet into the root directory. Run `npm install` to install required dependencies (check `package.json`). Then, run `npm start`.

  ## Usage
  The demonstration video can be shown below:
  - Open the application
  - Test the functionality (adding/subtracting funds)
  - Open the `Developer Tool` and go to `Application` tab
  - Check `Service Workers` tab and make sure the status indicates `running`
  - Check the `offline` box and check the functionality as shown in demo
  - Install app with PWA functionality

  Demo:
  ![demo](./demo/pwa-demo.gif)

  ## License
  This project is covered under MIT License.

  <details>
    <summary>
      See License
    </summary> 
  
  ```
  Copyright <2021> <Kevin Choi>

  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  
  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  ```
  </details>
  

  ## Contributing
  No contribution will be accepted at this moment.

  ## Tests
  There are no tests available in this application.

  ## Questions
  If you have any questions, please contact me via

  * Email: [kevchoi1028@gmail.com](mailto:kevchoi1028@gmail.com)

  * GitHub: [https://github.com/rhwlffk1028](https://github.com/rhwlffk1028)

  * Linkedin: [https://linkedin.com/in/kevchoi](https://linkedin.com/in/kevchoi)
