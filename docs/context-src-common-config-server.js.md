

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:17:46

This code file (server.js) is responsible for setting up and starting the server for an application. Its main purposes and key functionalities include:

1. Server Initialization:
   - Creates either an HTTPS or HTTP server based on the environment configuration.
   - Sets up SSL/TLS for secure connections in staging and production environments.

2. Port Listening:
   - Starts the server to listen on a specified port.
   - Logs server startup information, including the port and server URL.

3. Cron Jobs:
   - Sets up scheduled tasks using node-cron.
   - Runs periodic tasks for fetching order lists and checking order statuses every 10 minutes.
   - Executes functions to update campaign and insertion order statuses.

4. Error Handling and Graceful Shutdown:
   - Sets up event listeners for server startup and shutdown.
   - Implements a graceful shutdown process when receiving a SIGINT signal (e.g., Ctrl+C).

5. Modular Design:
   - Exports a startServer function, allowing for easy integration with other parts of the application.

Overall, this file serves as the central point for server configuration, initialization, and management of recurring tasks, ensuring the application runs securely and efficiently while handling server lifecycle events appropriately.
