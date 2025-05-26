# A Decentralized Certificate Verification System Using Blockchain
# Blockchain Certificate Verification System

This is a Flask web server that connects users, schools, and certificates to a blockchain-based certificate verification system. The goal of this system is to provide a secure and tamper-proof way of verifying educational certificates and degrees.

## Getting Started

## Prerequisites

- Python 3.6 or higher
- Flask
- Flask-RESTful
- Flask-CORS
- SQLAlchemy
- MySQL
- hardhat Ethereal network

## Installing

Clone the repository:

```
git clone https://github.com/queensk/Blockchain-Certificate-Verification-System.git
```

## start the frontend

```
cd frontend
```

install the react dependencies

```
npm i
```

start development server

```
npm start
```

## start backend application

Create a virtual environment and activate it.

Install the required Python packages:

```
pip install -r requirements.txt
```

Set the environment variables (see the Configuration section below).

Start the Flask web server:

```
python3 -m app.api.v1.app
```

Access the API documentation at http://127.0.0.1:5000/api/v1/status.

## Configuration

The following environment variables must be set in order to run the web server:

```
BCV_MYSQL_USER: The MySQL username.
BCV_MYSQL_PWD: The MySQL password.
BCV_MYSQL_HOST: The MySQL server hostname.
BCV_MYSQL_DB: The name of the MySQL database.
BCV_TYPE_STORAGE: The type of storage to use (db for MySQL or blockchain for a blockchain-based storage).
BCV_API_HOST: The hostname or IP address where the web server will listen for requests (default: 0.0.0.0).
BCV_API_PORT: The port where the web server will listen for requests (default: 5000).
BCV_ENV: The environment (e.g., dev, prod, etc.).
SECRET_KEY: The secret key used by Flask for session management.
```

## Blockchain Integration

This system supports two types of storage: MySQL and blockchain-based storage. To use blockchain-based storage, you must have a running Ethereum blockchain node and a smart contract that implements the certificate storage and verification logic.

- Starting the nodes

```
cd Backend/contracts
```

`npm i` to install requrimentest

- start nodes

```
npx hardhat node

```

- Deploy nodes

```

npx hardhat run scripts/deploy.js --network localhost

```

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
