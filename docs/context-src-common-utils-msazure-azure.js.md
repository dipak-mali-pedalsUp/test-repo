

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:20:18

This code file, named 'azure.js', is responsible for setting up and configuring the Azure Blob Storage client for use in the application. Its main purpose is to create a connection to Azure Blob Storage and provide access to a specific container. Here are the key functionalities:

1. It imports the necessary configuration from a config file and the BlobServiceClient from the Azure SDK.

2. It retrieves the Azure Storage connection string and container name from the config file.

3. It creates a BlobServiceClient using the connection string.

4. It then creates a ContainerClient for the specified container.

5. Finally, it exports the ContainerClient, making it available for use in other parts of the application.

This setup allows other parts of the application to easily interact with the specified Azure Blob Storage container, enabling operations like uploading, downloading, or deleting blobs (files) within that container.
