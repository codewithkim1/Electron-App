
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
1. Create Window: Initializes a browser window with specified dimensions (800x600).
2. Load URL: Loads a remote URL (http://google.com) into the created window.
3. Cross-Platform: Handles window behavior for different platforms (e.g., macOS).
   
### Getting Started
### Prerequisites

- Node.js
- npm (Node Package Manager)

### Installation

### Clone the repository

```bash
git clone git@github.com:codewithkim1/Electron-App.git

cd Electron-App
```
### Navigate into the directory

```bash
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

## Screenshot

![App Screenshot](/electronapp.png)
