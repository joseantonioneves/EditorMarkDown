# Markdown Editor

Yet another Chrome Markdown Editor.

## Features

* Save your data at real time
* Drag and drop a file to load it
* Ctrl/Cmd + S to save the source file
* Support Github Flavored Markdown syntax
* Support many languages highlight in editor and preview mode

## Installation

* https://chrome.google.com/webstore/detail/ekdcaddpmiodcipjfmffhhefijpdckaf

## Components

Repackage of markdown-editor with some modifications: https://github.com/jbt/markdown-editor

## Compilation

To compile the project, open a terminal in the project directory and run:

```
dotnet build
```

This will restore dependencies and build the project.

## Prerequisites

Before running the Markdown Editor project, ensure you have the following installed on your system:

- **A modern web browser**  
  (e.g., Chrome, Firefox, Edge, or Safari)

- **A local web server** (recommended for full functionality)  
  You can use either **Python 3** or **Node.js** to serve the files locally.

### Installation Instructions

If you do not have Python 3 or Node.js installed, follow these steps:

#### Python 3

- **Windows/macOS/Linux:**  
  Download and install Python 3 from [https://www.python.org/downloads/](https://www.python.org/downloads/).

- **Verify installation:**  
  Open a terminal or command prompt and run:
  ```sh
  python --version
  ```

#### Node.js

- **Windows/macOS/Linux:**  
  Download and install Node.js from [https://nodejs.org/](https://nodejs.org/).

- **Verify installation:**  
  Open a terminal or command prompt and run:
  ```sh
  node --version
  npm --version
  ```

Once installed, you can start a local server using the instructions in the **Execution** section below.

## Execution

### Compilation and Execution Steps

To use the Markdown Editor locally, follow these steps:

#### 1. Clone or Download the Repository

Download or clone this repository to your local machine.

#### 2. Start a Local Web Server

Some browser features (like file access) require running the app from a local web server.  
Open a terminal in the project directory and run one of the following commands:

**Using Python 3:**
```sh
python -m http.server 8000
```

**Using Node.js (if installed):**
```sh
npx serve .
```

#### 3. Open the Application in Your Browser

Navigate to:

```
http://localhost:8000/index.html
```

#### 4. Alternative: Open Directly

You can also open `index.html` directly in your browser, but some features may not work due to browser security restrictions.

---

**Requirements:**  
- Any modern web browser  
- (Optional) Python 3 or Node.js for running a local server

---

## Notes

- For other environments or configurations, adjust the commands accordingly.

## License

GNU GENERAL PUBLIC LICENSE Version 3
