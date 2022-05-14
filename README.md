# Super-Awesome-Text-Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The goal of this project is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. To build this text editor, I will start with an existing application and implement methods for getting and storing data to an IndexedDB database. I will use a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

Functionality should be as follows:

When I open my application in my editor I should see a client server folder structure. When I run `npm run start` from the root directory I find that my application should start up the backend and serve the client. When I run the text editor application from my terminal I find that my JavaScript files have been bundled using webpack. When I run my webpack plugins I find that I have a generated HTML file, service worker, and a manifest file. When I use next-gen JavaScript in my application I find that the text editor still functions in the browser without errors. When I open the text editor I find that IndexedDB has immediately created a database storage. When I enter content and subsequently click off of the DOM window I find that the content in the text editor has been saved with IndexedDB. When I reopen the text editor after closing it I find that the content in the text editor has been retrieved from our IndexedDB. When I click on the Install button I download my web application as an icon on my desktop. When I load my web application I should have a registered service worker using workbox. When I register a service worker I should have my static assets pre cached upon loading along with subsequent pages and static assets. When I deploy to Heroku I should have proper build scripts for a webpack application.

## Table of Contents

- [Technology Used](#technology-used)
- [Links](#links)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Technology Use

- [Node.js](https://nodejs.org/en/)
- [Express](https://www.npmjs.com/package/express)
- [Webpack](https://webpack.js.org/)
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

## Links

- [GitHub Repository](https://github.com/dlzinck/Super-Awesome-Text-Editor)

## Installation

```
npm install
```

## Usage

Start the server

```
npm run build
npm run start
```

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit).

Copyright (c) 2022 Drew Zinck II

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
