### Install instruction:
## Testing with Postman
1. Run "npm i" command in your terminal, to install all required libraries
2. Change DB pool configuration in "apps.js" file (14-20 lines) to yours
3. Open Postman programm and search for "Import" button
4. Import "Authentication-db.postman_collection.json" file into Postman
5. Go back to code terminal and run "npm run dev" command to start server

## Testing with Newman

1. Run "npm i" command in your terminal, to install all required libraries
2. Change DB pool configuration in "apps.js" file (14-20 lines) to yours
3. Run "npm run dev" command to start server
4. Open another terminal and run "newman run Authentication-db.postman_collection.json" command
