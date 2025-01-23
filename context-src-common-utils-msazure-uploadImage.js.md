

---
# High Level Context
## context
**Last Updated at:** 22/01/2025, 13:20:25

This code file defines a function called `uploadImage` which is responsible for uploading an image file to Microsoft Azure Blob Storage. Here's a breakdown of its key functionality:

1. It imports an Azure storage client from a local module './azure'.

2. The `uploadImage` function takes a file object as an argument, which is expected to contain properties like `originalname`, `buffer`, and `mimetype`.

3. It generates a unique blob name by combining the current timestamp with the original filename.

4. It uses the Azure storage client to get a reference to a block blob with the generated name.

5. The function then uploads the file's buffer to Azure Blob Storage, setting the content type to match the file's MIME type.

6. Finally, it returns the URL of the uploaded blob, which can be used to access the image.

This utility function simplifies the process of uploading images to Azure Blob Storage, handling the necessary Azure SDK calls and providing a clean interface for other parts of the application to use when they need to store images in the cloud.
