# Text-Editor-PWA
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description
With the goal of having a PWA to create notes or code snippets without an internet connection, I created a text editor PWA. 

When the application is opened in a code editor, a client server folder structure can be seen. Running `npm run start` from the root directory will start the backend and serve the client. When the text editor is opened IndexedDB has immediately created a database storage. When content is entered and the user subsequently clicks off of the DOM window the content in the text editor has been saved with IndexedDB. When the text editor is reopened after closing it the content in the test editor is retrieved from IndexedDB. 

The text editor can be downloaded to the user’s machine by clicking the Install button. When loading that application, there will be a registered service worker with static assets pre-cached.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Credits](#credits)
4. [Tests](#tests)
5. [Questions](#questions)
6. [License](#license)

## Installation
To install the necessary dependencies, run the following command:
    
    npm run install

To lauch backend server:

    npm run start

## Usage

https://shrouded-castle-09726-012f9748a213.herokuapp.com/

https://github.com/ericolson1977/Text-Editor-PWA


## Credits
Starter code provided by the instructional staff. 

NPM pachages used include:
    Express, IDB, Webpack and Babel

## Tests
n/a

## Questions
If you have any questions about the repo, open an issue or contact me directly at mr_tues_night@yahoo.com. You can find more of my work at [ericolson1977](https://github.com/ericolson1977).

## License
  This project is licensed under the MIT license.
