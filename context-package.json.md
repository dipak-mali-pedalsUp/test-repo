

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:08:04

This file is a `package.json` configuration file for a Node.js project named "impression-backend". Its purpose is to define the project's metadata, dependencies, and scripts. Key functionalities include:

1. Project Information:
   - Name: impression-backend
   - Version: 1.0.0
   - Main entry point: app.js

2. Scripts:
   - Defines a start script using nodemon for development, allowing automatic server restarts on file changes.

3. Dependencies:
   - Lists various npm packages required for the project, including:
     - Express.js for building the web server
     - Mongoose for MongoDB interaction
     - JSON Web Token (jsonwebtoken) for authentication
     - Axios for making HTTP requests
     - Multer and Multer-S3 for file uploads
     - Winston for logging
     - Various Azure and AWS SDK packages for cloud services

4. Development Dependencies:
   - Includes nodemon as a dev dependency for easier development workflow

5. Version Control:
   - Specifies the git repository information

This file serves as a central configuration for the project, managing its dependencies and providing information about how to run and maintain the application.
