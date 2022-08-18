# Insure Social

## **1. Prerequisites**

1. Node: v14.17.5
2. NPM: v6.14.14
3. Mongo: v4.4.3
4. Angular CLI: v10.2.3
5. NestJS CLI: v7.6.0
6. Rest API Client e.g [Postman](https://www.postman.com/downloads/)
7. Run ( *check if Node and NPM is installed* ):
   > **node -v**

   > **npm -v**
8. If you see versions you can proceed otherwise please visit [Node Official website](https://nodejs.org/en/).
#
## **2. Run the Application**
`(Skip to B if you do not have docker installed on your pc)`
### **A. Run on docker container**
1. Open on the terminal, navigate to root project and run:
   >  `docker compose up`
### **B. Install Angular CLI and NestJS CLI Globally *(Skip this step if you already have them installed)***
1. NestJS CLI
   > `npm i -g @nestjs/cli@7.6.0`
2. Angular CLI
	> `npm i -g @angular/cli@11.2.1`
#
### **C. Running the project**
1. ***Running the backend***
   - On the terminal, navigate to the backend directory
   - Run ( *Install all the dependencies* ):
      > *`npm install`*
	- Run ( *Run the backend* ):
		> *`npm run start:dev`*

2. ***Running the frontend***
   - On the terminal, navigate to the frontend directory
   - Run ( *Install all the dependencies* ):
      > *`npm install`*
   - Run ( *Run the frontend* ):
      > *`ng s -o`*
