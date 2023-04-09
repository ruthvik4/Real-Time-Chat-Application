# Real-Time-Chat-Application
A simple demo chat app built on Node.js, Express.js and Socket.io.

[Click here to read my Medium blog on this Basic Project](https://medium.com/@ruthvikreddy4724/how-to-build-a-real-time-chat-app-with-node-js-and-express-js-34311da4f658)

# Pre-requisites
To setup and run the project for local development / testing, you will need to use Node.js and NPM. I don't explicitly specify a minimum Node.js/NPM version for the app but I recommend going with whatever the latest LTS version is at the point in time you are setting things up. The minimum vesion of Node.js that I have tested this app on is 10.16.3.

Installers can be found here: https://nodejs.org/en/download

# Installation

You can clone the Repo to a local folder on your machine or download and extract the archive if you don't have Git installed.


Open a terminal window session, or the equivalent on your machine, and enter the following command to install all the Node modules needed to run the app:

`npm install`
`npm install express socket.io`

# Testing the chat app

Start the server by running the following command in your terminal or command prompt:
`node app.js`
Open a web browser and navigate to http://localhost:3000/. You should see the chat app’s main page.

Open a second web browser window or tab and navigate to the same URL.

In one of the windows, enter a message in the text input field and click the Send button. The message should appear in both windows.
# Sample Output

![image](https://user-images.githubusercontent.com/88588631/230762738-df1376ab-a21c-483a-8ab0-827761bf234e.png)

![image](https://user-images.githubusercontent.com/88588631/230762759-d750236a-2dfc-4f2e-b6be-82e99ac228c3.png)
