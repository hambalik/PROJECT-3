##  **PROJECT 3 IMPLEMENTATION/DOCUMENTATION (MERN STACK)**

## STEP 1 – BACKEND CONFIGURATION

### The backend configuration started with the ubuntu update and upgrade

`sudo apt update`



![sudo-apt-update](./images/sudo-apt-update.PNG)
![sudo-apt-update1](./images/sudo-apt-update1.PNG)

`sudo apt upgrade`

![sudo-apt-upgrade](./images/sudo-apt-upgrade.PNG)
![sudo-apt-upgrade1](./images/sudo-apt-upgrade1.PNG)
![sudo-apt-upgrade2](./images/sudo-apt-upgrade2.PNG)

### Getting the location of Node.js software from Ubuntu repositories

`curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -`

![capture-5](./images/capture-5.PNG)
![capture-6](./images/capture-6.PNG)

### Node.js installation followed

`sudo apt-get install -y nodejs`

![nodejs](./images/nodejs.PNG)

### Node installation was then confirmed
`node -v`

`npm -v`

![capture-7](./images/capture-7.PNG)

### Application code set up begin by creating a new directory for the To-do application

`mkdir Todo`

![todo](./images/todo.PNG)

### Followed by the initialisation of the project MERN

`npm init`

![npm-init](./images/npm-init.PNG)

### Confirmation of package.json in the todo folder

`ls`

![packagejson-ls](./images/packagejson-ls.PNG)

## Installation of Expressjs which serves as framework for Node.js

`npm install express`

![install-express](./images/install-express.PNG)

## Creation of index.js file in the Todo folder

`touch index.js`

![touch-index-creation](./images/touch-index-creation.PNG)

## Installation of dotenv

`npm install dotenv`

![dotenv](./images/dotenv.PNG)

## Saving codes in the index.js 

`vim index.js`

![vim-index.js1](./images/vim-index.js1.PNG)

## Starting of the server to confirm its working 

`node index.js`

![node-index,js](./images/node-index,js.PNG)

## . Opening up port 5000
## . Open up the web browser to access the created server using public IP or public DNS name, followed by the port :5000

![security-grp-edit](./images/security-grp-edit.PNG)

![welcome-to-express](./images/welcome-to-express.PNG)

## for each task of
. POST

. GET or

. DELETE
## routes folder was created which defines various endpoints that the To-do app depends on

`mkdir routes`

![mkdir-routes-cd-routes](./images/mkdir-routes-cd-routes.PNG)

## Then, cd into routes and created file api.js in the routes folder and open the api.js file

`cd routes`

`touch api.js`

`vim api.js`

![cd-routes](./images/cd-routes.PNG)

![touch-api](./images/touch-api.PNG)

![vi-api-js1](./images/vi-api-js1.PNG)

![vim-api-js](./images/vim-api-js.PNG)

## Mongoose is installed which is a Node.js package that makes working with mongodb easier

`npm install mongoose`

![npm-install.mongoose](./images/npm-install.mongoose.PNG)

## A new folder models created

`mkdir models`

![mkdir-models](./images/mkdir-models.PNG)

## Then I cd into  and todo.js file created inside the models folder

`cd models`

`touch todo.js`

![cd-models-and-touch-js](./images/cd-models-and-touch-js.PNG)

## Opened up the file todo.js created

`vim todo.js`

![vim-todo-js1](./images/vim-todo-js1.PNG)


![vim-todo-js](./images/vim-todo-js.PNG)


## api.js file was opened inside the routes directory

`vim api.js`

![vim-api-js1](./images/vim-api-js1.PNG)

![vim-api-js](./images/vim-api-js.PNG)

## mongoDB database was successfully created

![mongoDB](./images/mongoDB.PNG)

![mongoDB1](./images/mongoDB1.PNG)

## A file name .env was created in the file Todo directory

`touch .env`

`vi .env`

![touch-env1](./images/touch-env1.PNG)

![vi-env1](./images/vi-env1.PNG)

## I proceeded to update the index.js file to allow Node.js to connect to the database

` vim index.js`

![vim-index.js](./images/vim-index.js.PNG)

## I then started the server

` node index.js`

![nodeindex](./images/nodeindex.PNG)

## CRUD operation was performed using postman app to test functionality of API

`node index.js`

![post-all-over-again](./images/post-all-over-again.PNG)

![get-all-over-again](./images/get-all-over-again.PNG)

## STEP 2 – FRONTEND CONFIGURATION

## In root directory (Todo directory)  create-react-app command was used to scaffold our app by creating a directory called client

`npx create-react-app client`

![npx-create-react](./images/npx-create-react.PNG)

![npx-create-react1](./images/npx-create-react1.PNG)

![npx-create-react2](./images/npx-create-react2.PNG)

## Concurrently was installed as one of depeendencies which is used to run more than one commands at the same time from the same window terminal before testing the react-app

`npm install concurrently --save-dev`

![npm-install-concurrently](./images/npm-install-concurrently.PNG)

## Nodemon installed which is used to run and monitor the server

`npm install nodemon --save-dev`

![npm-install-concurrently](./images/npm-install-concurrently.PNG)

## Nodemon installed which is used to run and monitor the server

`npm install nodemon --save-dev`

![npm-install-nodemon](./images/npm-install-nodemon.PNG)

## The package.json file in the Todo folder was edited

`vim package.json`

![package-json](./images/package-json.PNG)

## Configuring proxy in package.json
. Firstly change directory to client  
. Open the package.json file  
. Add the key value pair in the package.json file "proxy": "http://localhost:5000"

`cd client`

`vi package.json`

![proxy](./images/proxy.PNG)

## Nodemon installed which is used to run and monitor the server

`npm run dev`

![npm-install-nodemon](./images/npm-install-nodemon.PNG)

## Accessing the App on the web browser

![learn-react](./images/learn-react.PNG)

## Creating react components
. From Todo directory, I cd into client  
. Then I moved to the src directory  
. A folder known as components was created in the src folder  
. Then I moved into the created components folder  
. Inside ‘components’ directory the following three files Input.js, ListTodo.js and Todo.js are created

`cd client`

`cd src`

`mkdir components`

`cd components`

`touch Input.js ListTodo.js Todo.js`

![mkdir-components](./images/mkdir-components.PNG)

## Opened input.js file

`vi Input.js`

![vi-input](./images/vi-input.PNG)

## Making use of Axios
. I moved to the src folder  
. And then moved to clients folder  
. Then, I installed AXIOS

`npm install axios`

![npm-install-axios](./images/npm-install-axios.PNG)

## To ‘components’ directory

`cd src/components`

## Then I opened the ListTodo.js

`vi ListTodo.js`

![listTodo-and-todo](./images/listTodo-and-todo.PNG)

![listTodo](./images/listTodo.PNG)

## Then I opened the ListTodo.js

`vi ListTodo.js`

![listTodo-and-todo](./images/listTodo-and-todo.PNG)

## Then the Todo.js file is edited

`vi Todo.js`

. Move to src folder  
. Open vi App.js and edited as stated in the documentation

`vi App.js`

![vi-api-js1](./images/vi-api-js1.PNG)

![vi-api-js](./images/vi-api-js.PNG)

## In the src directory the App.css was opened and edited as stated in the documentation

`vi App.css`

![vi-app-css](./images/vi-app-css.PNG)

## In the src directory the index.css was opened and edited as stated in the documentation

`vi index.css`

![vi-index-css](./images/vi-index-css.PNG)

. Then went back to the Todo directory to run the below code

`npm run dev`

![npm-run-dev](./images/npm-run-dev.PNG)

![npm-run-dev1](./images/npm-run-dev1.PNG)

. I then finally log into the public IP on the browser to confirm functionality of the TO-DO APP

![my-todo-web-page](./images/my-todo-web-page.PNG)







