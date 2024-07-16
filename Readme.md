
## Electron App Project

This project is a simple Electron application that creates a desktop window and loads a remote URL (https://example.com) into the window. Electron allows for the development of desktop applications using web technologies such as JavaScript, HTML, and CSS.

## Directory Structure
 ```bash
├── main.js
├── node_modules
├── package.json
├── package-lock.json
└── preload.js (optional)
```

## Features
Create Window: Initializes a browser window with specified dimensions (800x600).
Load URL: Loads a remote URL (http://google.com) into the created window.
Cross-Platform: Handles window behavior for different platforms (e.g., macOS).
Getting Started
Prerequisites
Node.js
npm (Node Package Manager)
Installation

### Clone the repository

```bash
git clone https://github.com/codewithkim1/electron-app.git

cd Electron-App
```

### Install dependencies

```bash
npm install 
```

### Running the Application
To start the Electron application, run the following command
```bash
npm start 
```

## Screenshots

![App Screenshot](/electronapp.png)