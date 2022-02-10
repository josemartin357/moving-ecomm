# Moving E-commerce
![License: MIT](https://img.shields.io/apm/l/vim-mode?style=for-the-badge)

MERN application that allows a moving company offer products and services. The idea behind this product is to offer local small moving companies a platform where they can also function as an e-commerce.
In this application, a user can browse products, add them to the cart and make a payment using Stripe.

## Technical Concept

It uses MongoDB and the Mongoose ODM for the databases. It uses queries and mutations for retrieving, adding, updating, and deleting data. It is part of Schemas folder on server side. The app uses GraphQL with a Node.js and Express.js server. It is deployed at Heroku. See Heroku link below. It uses React.js on the front end. It is interactive. It accepts user's input when a user wants to add an item to the cart or remove it. It includes JWT (Json Web Token) authentication. It uses Ant design component library. 

## To run App

To start this app for the first time from your local host, do the following: run `npm install` from the root folder to install and update all dependencies needed. Then, run `npm run seed` to load the data in the seeds file. Theb, run the command `npm run build` to build the application and finally run the command `npm run develop` to launch the application in localhost:3000. 

## Application sample
![image](https://user-images.githubusercontent.com/88174852/151672693-e3fe57ed-9308-41e6-a88e-0e302fbd6570.png)


## Technologies Used
ReactJS
<br/>
NodeJS
<br/>
GraphQL
<br/>
MongoDB
<br/>
Express.js
<br/>
Stripe
<br/>
JWT
<br/>
Ant design
<br/>
Heroku

## Testing
In this application, we are using reducers to develop unit tests. Reducers are great at returning new state after applying the actions to the previous state. 
<br/>
Here, we call reducers with an input state and action. Source: https://redux.js.org/usage/writing-tests
<br/>
To run tests, go to client folder and run the command `npm test`.
Cases being tested:  UPDATE_PRODUCTS, ADD_TO_CART, UPDATE_CART_QUANTITY, REMOVE_FROM_CART, ADD_MULTIPLE_TO_CART, CLEAR_CART, TOGGLE_CART,
<br/>
<br/>
![Screen Shot 2022-02-10 at 9 02 55 AM](https://user-images.githubusercontent.com/83382332/153442547-9612a996-7c56-4ba3-b7de-1ae567615a32.png)


## Links
### Deployed link
https://twomenandahorse.herokuapp.com/
### GitHub Repo
https://github.com/josemartin357/moving-ecomm

## Future development
Currently working on the following ideas:
<br/>
Redoing concept of application so rather than being an e-commerce business for one company, it can instead be a platform where users can post their moving services for short moves and/or users can make a moving reservation.
<br/>
Contact component in Nav bar which will have static contact info and a contact form using EmailJS.
<br/>
My orders component which will carry all the orders made by logged-in user.


## Contributors 
### Martin Bedoya - client side: mutations, queries, components, tests, last-minute styling.
### Mark Sammis - overall project management, powerpoint
### Allen Cheslik - Database and Seeds, Stripe, Serviceworker Implementations
### Talhah Awan - styles, ant-components
### Alexander Umnov - front end, readme, powerpoint
