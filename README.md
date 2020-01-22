# Parky

## Overview

Need parking in Philly? Enter Parky, the airBnb for parking spots. With Parky, users may create parking listings, search for spaces by address, reserve spaces, and update or cancel reservations across a range of days in Philly.

## Getting Started

Create an account, or use our demo accounts:

> "Power User"
> Username: user
> Password: test

> "Listing Owner"
> Username: owner
> Password: test

### Login

Users may login using their account information or sign up for a new account by clicking the Sign Up link.

<img src="./assets/login.png" width="600">

### Search

After logging in, users are redirected to the Search page where users may search for parking spots available for rent by location and date. Users can also complete bookings from this page via the "Book Now" buttons in the search results.

Our app assumes that renters would book a spot for an entire day, so we support searches across individual days or a range of dates. 

<img src="./assets/search.png" width="600">


### Create Listing

Users may create listings for their own parking spots by clicking Create in the nav bar. This is accomplished with a stepper component in wihich users are guided through defining their listing, submitting the listing's availability, and confirming its details.

<img src="./assets/create.png" width="600">

### Dashboard

<img src="./assets/reserv.png" width="600">

The profile dashboard offers two views: Listings and Reservations.

The Listings view allows users to see all of their active listings as well as edit availability & details, see earnings from listings, and remove listings from the app.

The reservation view allows users to see all upcoming reservations on parking spots with the ability to cancel reservations entirely or partially (for multi-day reservations).

## Technologies Used

- React
- Express
- Node.js
- MongoDB
- JavaScript (ES6)
- Mongoose
- Passport.js

### Node Packages used:

- Mongoose
- DotEnv
- Material UI
- Axios
- Moment.js

## Authors:

- Ana Chernov - https://github.com/purpetrator
- Chris Gottshalk - https://github.com/cgottshalkjr
- Tomas Gear - https://github.com/nexio-t
- Valentyna Abraimova - https://github.com/Abraval
