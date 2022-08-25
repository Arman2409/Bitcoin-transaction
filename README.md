# Bitcoin Transaction

Transaction is handled by bitcore-lib module of Node.js.The sochain.com service is used to get unsped txos and
also to send the transaction.

## Running the project

To run the project and create your own transaction, you will need to run the following commands:

*** npm install ***

then you will need to add the .env file with following variables:


MY_ADDRESS, PRIVATE_KEY, DESTINATION_ADDRESS


After that configure the amount,fee in index.js file and run the following command:

***npm run start ***

and  the transaction will be created.


