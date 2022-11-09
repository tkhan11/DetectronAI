<h1 align="center">
  <br>
    <img src="https://github.com/tkhan11/DetectronAI/blob/master/assets/images/logos/detectronAI-fill.png" alt="DetectronAI" width="200">
  <br>
  Sharingan
  <br>
</h1>

<h4 align="center">
A Real-Time object detection app, built with <a href="https://www.electronjs.org/">Electron</a>, and <a href="https://www.tensorflow.org/js/">Tensorflow.js</a>.
</h4>

<p align="center">
  <a><img alt="MIT License" src="https://img.shields.io/apm/l/atomic-design-ui.svg?"></a>
  <a><img alt="Github Release" src="https://img.shields.io/badge/release-v1.0.2-blue"></a>
</p>

<p align="center">
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#installation">Installation</a> •
  <a href="#run--package">Run & Package</a> •
  <a href="#authors">Author</a> •
  <a href="#license">License</a>
</p>

<img alt="Screenshot 1" src="https://github.com/tkhan11/DetectronAI/blob/master/assets/images/screenshots/2.png">
<img alt="Screenshot 2" src="https://github.com/tkhan11/DetectronAI/blob/master/assets/images/screenshots/3.png">

## Prerequisites

- Git is need to clone repository on your machine.
- npm is needed to install packages.
- Node.js is needed to run DetectronAI.

### Ubuntu

Install git, Node.js and npm on your machine running Ubuntu:

```bash
$ sudo apt-get install git-core
$ sudo apt install nodejs
$ sudo apt install npm
```
### Windows

Use the official links for downloading on Windows:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm)

Run the following commands to confirm if the installation was successful:

```bash
$ git --version
$ node --version
$ npm --version
```

## Installation

Clone the repo and cd into the directory:

```bash
$ git clone https://github.com/tkhan11/DetectronAI.git
$ cd DetectronAI
```

Then install the node-modules in package.json:

```bash
$ npm install
```

## Run & Package

Run the app with the following command:

```bash
$ npm start
```

Package the app with [electron-packager](https://www.npmjs.com/package/electron-packager):

For Windows:
```bash
$ npm run package-win
```

For Linux:
```bash
$ npm run package-linux
```

For Mac:
```bash
$ npm run package-mac
```

## Author

- **Tanveer** - [Github](https://github.com/tkhan11)

## License

[MIT License](https://github.com/tkhan11/DetectronAI/blob/master/LICENSE) | Copyright (c) 2022 Tanveer Khan
