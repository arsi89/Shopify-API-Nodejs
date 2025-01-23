# Shopify-API-Nodejs
Accessing Shopify API using Nodejs library

This application is intended to streamline the administration of products within a Shopify store. It enables users to add new products, adjust inventory quantities, access product information, and display all products currently available in the store. Developed with Node.js and the Shopify API Node library, it provides an effective means of engaging with the Shopify API.

**Configuration**

Create a .env file in the project root and add the following environment variables:
```
SHOP_NAME=your_shop_name
API_KEY=your_api_key
API_SECRET=your_api_secret
```
Replace your_api_key,your_shop_name, and your_api_secret with your Shopify store's details.
Usage

The script can be run using Node.js. To start the script, use:

```
node main.js
```
Call the specific function calls to perform different actions like listing, creating a product, listing locations, updating stock, etc.
