# Angular Ecommerce Web App

## Getting Started

The app can be installed by cloning the git repository

```bash
git clone https://github.com/asimsharf/ecommerce-angular.git 
```

Then cd into both directories and run npm install

```bash
cd folder-name
cd backend
npm run install
cd.. // return to folder-name
cd client
npm run install
```

<br/>

After the entire installation you need to run the server and the client by running this commands each in its own directory

**backend**

```bash
npm run dev
```

**client**

```bash
ng serve
```

<br/>

## Prerequisites

You will need to have node and npm installed. In addition you will need a MySQL server running in order to have full functionality of the application

<br/>

## Environment Variables

Create a folder called env in the root of the backend directory and create a development.env file.

**Change DB variables to match your MySQL setup**

```bash
PORT=5000
DB_HOST='localhost'
DB_USER='root'
DB_PASSWORD=''
DB_NAME='myapp'
```
