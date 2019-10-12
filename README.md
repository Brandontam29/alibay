# Alibay #
Alibay is a simple website that was created to practice building e-commerce fundamental features. 

Those features used most notably React, Redux, and MongoDb for implementation.


### Project description ###
This website allows users to create accounts and browse through entire catalogues of item for sale. To facilitate buying, there is a search and filter by category function. At the end of their shopping, users can view their cart, checkout and the product inventory is updated. Furthermore, users with accounts can also put items for sale.

Features include:
  - Login / Signup system
  - Account viewing
  - Browse and add to cart
  - Filter items by search or category
  - View cart and Checkout
  - Sell items
  
### View Project ###
Project will be available for viewing soon.
This project unfortunately cannot be deployed due to Mongo Database restrictions.

### Notable Technologies ###
This website uses Javascript as its main language, and React as the framework. 

#### Redux ####
Tracks website wide activities to display information accordingly.

Information tracked by the store
```
 {
    loggedIn: false,    //whether the user is logged in or not
    searchQuery: "",    //display what the user is searching
    userData: {},       //store user data for quicker rendering
    modifyProfile: false,   //display input boxes for user to change profile information
  }
```

#### State ####
Tracks what is written in input boxes. It is used for Login  / Signup, but also instant Search filter.

#### All technologies include ####
  - Front-end: React.js, Redux, HTML, CSS
  - Backend: Node.js, Express, MongoDB
  - Other: Git, Github, NPM, Yarn

