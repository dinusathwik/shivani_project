# collaboration tool

## how to run this project

 > Please ensure that Node.js is installed on your machine. Subsequently, execute this project separately for both the backend and frontend components. Additionally, you need to have a MongoDB server running on your machine. Follow the below steps to run the project:
 1. Clone this repository
 2. Navigate to the backend directory and run `npm install` to install the necessary dependencies
3. Run `npm start` to start the backend server
4. Navigate to the frontend directory and run `npm install` to install the necessary dependencies
5. Run `npm start` to start the frontend server
6. Open your browser and navigate to `http://localhost:3000/` to view the application

## Troubleshooting
while running forntend server `ERR_OSSL_EVP_UNSUPPORTED` error is thrown, to resolve this error run the following command in the terminal
```bash
npm install webpack@latest react-scripts@latest
```
```bash
export NODE_OPTIONS=--openssl-legacy-provider
```
Then run `npm start` to start the frontend server.

> in backend you have .env file, which contains the environment variables, you can change the values of the variables as per your requirements.
