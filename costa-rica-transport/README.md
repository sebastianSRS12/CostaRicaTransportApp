# Costa Rica Transport Project

## Overview
The Costa Rica Transport project is a full-stack application designed to facilitate transportation services in Costa Rica. It consists of a client-side application built with modern web technologies and a server-side application that handles data management and business logic.

## Project Structure
```
costa-rica-transport
├── client                # Client-side application
│   ├── package.json      # Configuration for client application
│   ├── src               # Source files for client application
│   │   └── index.ts      # Entry point for client application
│   └── android           # Android build files
│       └── gradlew       # Gradle wrapper for building Android app
├── server                # Server-side application
│   ├── package.json      # Configuration for server application
│   └── src               # Source files for server application
│       └── index.ts      # Entry point for server application
├── .github               # GitHub Actions workflows
│   └── workflows
│       ├── ci.yml        # Continuous Integration workflow
│       └── cd.yml        # Continuous Deployment workflow
└── README.md             # Project documentation
```

## Setup Instructions

### Prerequisites
- Node.js (version 18 or higher)
- npm (Node package manager)
- MongoDB (for server-side application)
- PM2 (for process management on the server)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/costa-rica-transport.git
   cd costa-rica-transport
   ```

2. **Set up the client:**
   ```bash
   cd client
   npm install
   ```

3. **Set up the server:**
   ```bash
   cd server
   npm install
   ```

### Running the Application

- **Start the server:**
  ```bash
  cd server
  npm start
  ```

- **Start the client:**
  ```bash
  cd client
  npm start
  ```

### Testing

- To run tests for the client:
  ```bash
  cd client
  npm test
  ```

- To run tests for the server:
  ```bash
  cd server
  npm test
  ```

### Deployment

The application can be deployed using the Continuous Deployment workflow configured in GitHub Actions. Ensure that the necessary secrets are set in the repository settings for deployment to work correctly.

## Usage

Once the application is running, you can access the client-side application in your web browser and interact with the server-side API for data management.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.