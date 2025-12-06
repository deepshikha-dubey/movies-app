# movies-app

# Introduction

This repository is the result of the tutorial to develop your first MERN application and you can find it [here](https://medium.com/@samarony.barros/how-to-create-your-first-mern-mongodb-express-js-react-js-and-node-js-stack-7e8b20463e66)

## What you should install?

For this project, I decided to use the MERN (MongoDB, Express.js, React.js, and Node.js) technology.
![mern](https://miro.medium.com/max/678/1*dqvlaszRLvoPmARpOlLN9A.png)

Firstly, you should install

-   [Mongo](https://www.mongodb.com/) 4.0.4+
-   [ExpressJS](https://expressjs.com/) 4.16.3+
-   [ReactJS](https://reactjs.org/) 16.5.0+
-   [Node](https://nodejs.org/en/) 11.4.0+ (It's recommended to use 10.15.1 LTS)

## Download

You can download the folder on my [GitHub](https://github.com/samaronybarros/) or you can do this directly on [this link](https://github.com/samaronybarros/movies-app).

If you have git installed on your PC, you just need do as follow:

```
$ git clone https://github.com/samaronybarros/movies-app.git
```

## Configuring App

If you have all the prerequisites installed you should verify if your MongoDB is up.

```
$ cd movies-app
$ cd server
$ yarn install
$ nodemon index.js
```




```
$ cd movies-app
$ cd client

.	Now, you need to modify some files. Type vim ./movies-app/client/src/api/index.js.
.	Then, change the base_url into the following format. Here, replace EC2_IP:3000 with your <instance_ip_address>:3000.
<img width="981" height="512" alt="image" src="https://github.com/user-attachments/assets/dcdbba16-97ac-4eaf-ab3e-51ccae376b72" />


$ cd server
.	Now, type vim ./movies-app/server/db/index.js.
.	Next, replace the ip_address with ‘mongo’ as shown in the screenshot below.
<img width="981" height="404" alt="image" src="https://github.com/user-attachments/assets/96ebb2b3-c5de-4e54-bf88-6df845ca2459" />

. Configure your security groups to open the required ports 80 and 8000.

.	Creating Dockerfiles for client and server applications

.	Create a docker-compose.yml file.
.	Next, type sudo docker-compose up -d to start the containers.
.	Then, go to your browser and type the URL http://<ip_address>:8000/. You can see your app up and running.



$ yarn install
$ yarn start
```
