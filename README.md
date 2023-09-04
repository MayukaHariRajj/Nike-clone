# Nike-clone

<h1 align="center">Nike Clone</h1>
<h3 align="center"><a href="https://mohit-nikeclone.netlify.app/"><strong>Want to see live preview »</strong></a></h3>

<p align="center">
  <br />&#10023;
  <a href="#Demo">View Demo</a> &#10023;
  <a href="https://github.com/m-sehrawat/Nike-Clone/issues">Report Bug</a> &#10023;
  <a href="#Getting-Started">Getting Started</a> &#10023; 
  <a href="#Install">Installing</a> &#10023;
  <a href="#Contact">Author</a> &#10023;
</p>


Nike Clone is MERN Stack e-commerce web application that allows you to buy shoes & clothes online with payment gateway integration. It has a variety of categories, just visit the product listing page and you will see all the products, apply filters as per your need and in just a few clicks you can buy any products from the website. This project is just for personal project purpose.

![cover](https://user-images.githubusercontent.com/91532881/175955112-da88c18c-ac5e-455a-9ac5-047c7db4f894.png)

<br />

## Screens ( All screens are responsive along with Dark Mode)
- Homepage / Landing Page
- Product Listing Page with Filters
- Product Description Page
- Cart Management Page
- Wishlist/Favourites Management Page
- Checkout with Address Management Page
- Login / Logout Page
- Signup Page
- Order Summary Page


<br />


## 🚀 Features
- Login and Signup User Account
- JWT (Json Web Token) Authentication and BcryptJS Password Hashing 
- Product Filters Based on Price, Category, Size, Color and Gender
- Product Sorting Based on Price, Rating and Name
- Product Filtering and Sorting works together 
- My Orders Section for details of all ordered item
- Wishlist Add and Remove Items
- Cart Add and Remove Items 
- Cart Update Quantities 
- Address Management
- Order Summary
- Coupons provided for discount
- Razorpay Payment Gateway
- Darkmode available

<br />

## Glimpses of Nike-Clone 🙈 :


<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955122-200a6ccb-54a5-4f39-9bc2-cd3ba3a4d102.jpeg" alt="home" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955109-b51e3e81-4cd8-4f00-a8cd-873c82882a15.png" alt="coupons" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955141-44aefea0-a9ee-4c3a-93e0-094ca9214e54.jpeg" alt="signup" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955129-e5392377-e72a-4868-883f-5a244fc9bc87.jpeg" alt="login" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955097-9fe2e5a5-b4f4-4c1f-beb7-4080186e5a17.jpeg" alt="allProducts" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175957017-3530fe22-46ae-4bf7-a645-55f7a5f25ed9.jpeg" alt="men" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955142-dd33e21a-49a9-4aeb-89e7-edb3e871828f.jpeg" alt="women" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955126-2874a5c1-8655-40ab-b9ce-67275139e70e.jpeg" alt="kids" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955114-1090036d-2e73-46fa-8aca-8ef9ffab1724.jpeg" alt="description" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955117-edff5eaf-7507-4580-b3b8-3aea6c089840.jpeg" alt="descriptionDark" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955106-867749b1-4838-40dc-b184-145f10d1eec2.jpeg" alt="cart" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955107-f93e13a0-6c50-46e8-a5f3-09d15421e97b.jpeg" alt="checkout" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955137-828f89b2-648e-4a68-885a-fa3f3f29b55c.png" alt="razorpay" /></td>
    <td><img src="https://user-images.githubusercontent.com/91532881/175955133-96792a4b-7e70-4e1e-a5cf-999da70a9c95.jpeg" alt="orders" /></td>
  </tr>
</table>

<br />

## Test Coupon Codes
```
NIKE5 (for 5% Off)

NIKE10 (for 10% Off)

NIKE15 (for 15% Off)

NIKE20 (for 15% Off)

NIKE25 (for 25% Off)

NIKE30 (for 30% Off)
```



<br />


<h2>Demo</h2>

[Click here to see the presentation video of this project](https://www.linkedin.com/posts/m-sehrawat_reactjs-nike-nikecareers-activity-6947552300534042624-me2_?utm_source=linkedin_share&utm_medium=member_desktop_web)


<br />


## Getting Started

This project was built using React, Redux, Chakra UI, HTML, CSS, JavaScript, Rest API, Node JS, Express and MongoDB with JWT and RazorPay integration. It is an e-commerce web application and for running on your local environment you should follow these guidelines.


### Prerequisites

- NPM
- Node JS
- MongoDB

### Setup


The project repository can be found in [GitHub link](https://github.com/m-sehrawat/Nike-Clone) or just clone the project using this command.


```
Using HTTPS

# git clone https://github.com/m-sehrawat/Nike-Clone.git
```

+ Open terminal on your workspace with

```
cd /home/workspace/Nike-Clone
```


## Install

Install NPM

Check that you have node and npm installed

To check if you have Node.js installed, run this command in your terminal:


```
node -v
```

To confirm that you have npm installed you can run this command in your terminal:


```
npm -v
```

To confirm that you have MongoDB installed you can run this command in your terminal:


```
mongo -v
```


To install all the dependences of the project, run the following command:


```
cd client

npm install

cd ../

cd server

npm install
```


To run the application got to the client folder and run the following command:

```
npm start
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file in server folder

`JWT_ACCESS_KEY`

`MONGO_PATH`

`RAZORPAY_KEY_ID`

`RAZORPAY_KEY_SECRET`



### Tools used on this project

- Visual Studio Code
- Vite-JS template
- MongoDB compass
- Razorpay Dashboard to monitor payments

<br />


