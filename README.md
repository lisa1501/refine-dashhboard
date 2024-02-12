# Yariga Dashboard

## Description

Developed React-based CRUD, a fully functional dashboard that allows users to customize UI without constraints by applying Refine which is headless by design and offers unlimited styling and customization possibilities.
Provided a safe and easy way for users to log in and register using Google Auth. Stored user-uploaded images on the cloud by using Cloudinary. Implemented data filters feature, giving users the ability to quickly search properties by filtering a combination of attributes: name, price, property type and pagination
<br>

[Click here to see it in action!](https://halisa-yariga-app.netlify.app)
<br>
[Sperate repository links - client](https://github.com/lisa1501/Dashboard-Application-client)
<br>
[Sperate repository links - server](https://github.com/lisa1501/Dashboard-Application-server)
## Installation

- `git clone https://github.com/lisa1501/refine-dashhboard.git `
- `cd refine-dashhboard`
- install npm on client and server. do the cd on 2 separate terminals
  - `cd client`
  - `nvm use 18.13.0`
  - `npm install`
  - `cd server`
  - `nvm use 18.13.0`
  - `npm install`
 - in your server terminal, run npm start
 - in your client terminal, run npm run dev
- This project uses mongoose. Please install mongoose to your computer if you don't have it.

- Next create a .env file in server. It should contain the following information.
```bash
    MONGODB_URL = 
    CLOUDINARY_CLOUD_NAME = 
    CLOUDINARY_API_KEY = 
    CLOUDINARY_API_SECRET = 
    PORT=8080
```
- Next create a .env file in client. It should contain the following information.
```bash
   REACT_APP_GOOGLE_CLIENT_ID = 
```
## 

![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/signin.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/dashboard.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/properties.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/addproperty.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/propertyDetail.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/agentList.png)
![image](https://github.com/lisa1501/Dashboard-Application-server/blob/main/images/myProfile.png)



## Documentation 

https://github.com/refinedev/refine

## MVP

There are the minimum must-haves for the project

1. Sign in With Google Account

2. Agents CRUD their properties

3. Read properties by searching by title, sorting by price, filtering by property type and pagination

4. Easy to read all agent contact information

## Technologies Used

1.  JavaScript
2.  TypeScript
3.  MongoDB
4.  React Router
5.  React
6.  Theme CHange 

## Future Updates

1.  Users adds reviews to the properties

2.  Users could send messages to the agents



  
