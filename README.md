# warehouse-api

To start and test the Node.js application with the API endpoints for adding, deleting, updating, and listing items in the inventory, follow these steps:

Install Node.js and npm:
Ensure Node.js and npm (Node Package Manager) are installed on your system. You can download and install them from the official Node.js website: https://nodejs.org/
Create a New Directory:
Create a new directory for your Node.js project and navigate to it in your terminal or command prompt.
Initialize a Node.js Project:
Run npm init -y in your terminal to create a package.json file with default settings.
Install Required Packages:
Install the required packages (express and body-parser) by running the following command in your terminal:
bash
Copy code
npm install express body-parser
Create the Node.js Application:
Copy the Node.js code with the API endpoints (including adding, deleting, updating, and listing items in the inventory) into a file named app.js within your project directory.
Start the Node.js Server:
In your terminal, run the following command to start the Node.js server:
bash
Copy code
node app.js
You should see a message indicating that the server is running on a specific port (e.g., Server is running on port 3000).
Testing the Endpoints:
You can test the API endpoints using tools like Postman, curl, or by sending HTTP requests from your browser.
To list all items in the inventory, send a GET request to http://localhost:3000/api/warehouse/inventory.
To add a new item to the inventory, send a POST request to http://localhost:3000/api/warehouse/inventory/add with a JSON payload containing the new item's data.
To delete an item from the inventory, send a DELETE request to http://localhost:3000/api/warehouse/inventory/delete/:id (replace :id with the actual ID of the item you want to delete).
To update an item in the inventory, send a PUT request to http://localhost:3000/api/warehouse/inventory/update/:id (replace :id with the actual ID of the item you want to update) with a JSON payload containing the updated item data.
Verify the Results:
After sending requests to the API endpoints, verify the results by checking the responses and accessing http://localhost:3000/api/warehouse/inventory to see the updated inventory data.
