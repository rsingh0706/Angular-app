
# Angular App Setup Guide


# Project Overview
 
This project is an Angular web application developed using Angular, a popular open-source front-end framework maintained by Google.


# Prerequisites

Before you begin, ensure you have the following installed on your Linux system:


## Linux Essentials

Update your package list and install curl and git:

```bash

sudo apt update
sudo apt install curl git -y
```

## Install Node.js and Angular CLI

To install Node.js and the Angular CLI:

1. Update your system:

```bash

sudo apt update
```
2. Install Node.js (version 18.x):

```bash

curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install nodejs -y
```
3. Install the Angular CLI globally:

```bash
 
sudo npm install -g @angular/cli
```

## Verify the installation

```bash

node -v (v18.20)
npm -v  (10.7)
ng version
```

#### How to Set Up and Run the Angular Application

Follow these steps to set up and run the Angular project on your local machine:


1. Clone the repository

```bash

https://github.com/rsingh0706/Angular-app.git
```

2. Navigate into the project directory

```bash

cd angular-app
```

3. Install Dependencies

```bash

npm install 
```

4. Serve the application

```bash

ng serve
```

By default, the app will be available at http://localhost:4200

### Additional Configuration (Optional)

* If you need to change the default port (4200), use the following command:

```bash
ng serve --port 4300
```
* If you want the server to be accessible on your local network:

```bash
ng serve --host 0.0.0.0
```

