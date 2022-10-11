## PROJECT 4 MEAN

### Step 1: Install NodeJS

`sudo apt install -y nodejs`

![sudo apt install -y nodejs](./Images/sudo-apt-install-y-nodejs-new.PNG)

### Step 2: Install MongoDB

`sudo apt-key adv --keyserver`

![Install apt key](./Images/sudo-apt-key-adv-keyserver.PNG)

`echo "deb`

![Install echo deb](./Images/echo-deb-new.PNG)

`sudo apt install -y mongodb`

![Install -y mongoDB](./Images/Sudio-apt-install-y-mongoDB.PNG)

### start mongodb Server

`sudo service mongodb start`

![Install start mongoDB](./Images/Sudo-start-mongoDB.PNG)

`Verify that the service is up and running`

![Install mongoDB Systemctl](./Images/Sudo-systemctl-mongoDB-running.PNG)

### Install npm – Node package manager.

`sudo apt install -y npm not run because it is part of nodeJS 18.x installation`

### Install body-parser package

`sudo npm install body-parser`

![npm install body-parser](./Images/Sudo-npm-install-body-parser.PNG)

`mkdir Books && cd Books`

`npm init `

![npm init](./Images/npm-init.PNG)

`vi server.js`

![vi server](./Images/servernew.png)

### Step 3: Install Express and set up routes to the server

`sudo npm install express mongoose`

![Install express](./Images/Sudo-npm-install-express-mongoose.PNG)

`mkdir apps && cd apps`

`vi routes.js`

![vi routes](./Images/cat-vi-routes-js.2.PNG)

`mkdir models && cd models`

`vi book.js`

![vi books](./Images/cat-book-js.PNG)

### Step 4 – Access the routes with AngularJS

`mkdir public && cd public`

`vi script.js`

![vi scrpits.js](./Images/cat-scripts-js.2.PNG)


`vi index.html`

![vi index.html](./Images/cat-index-html.PNG)


### Start the server by running this command:

`node server.js`

![node server.js](./Images/nodejsnew.PNG)

`curl -s http://localhost:3300`

![curl](./Images/curlnew2.PNG)

### open TCP port 3300 in your AWS Web Console for your EC2 Instance

`launch address on Web browser`

 ![web browser](./Images/web-browser.PNG)

 ![web browser](./Images/test.PNG)

 ### The End of Project Four

 ## THANK YOU