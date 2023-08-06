This is the clone of an E_commerce website known as [SHOPPERS STOP](https://www.shoppersstop.com) build using Node js, EJS,  Express js, and Mongoose. We started this project as a six member team during the third unit construct week organised at Masai School, Bengaluru, Karnataka. 

## Basic inference about the company

Shoppers Stop is an Indian department store chain, owned by the K Raheja Corp. There are 86 stores across 40 cities in India, with clothing, accessories, handbags, shoes, jewellery, fragrances, cosmetics, health and beauty products, home furnishing, and decor products.

## Added Functionalities

### The application displays a virtual bags store that contains virtual products and contact information. User can do the following:

* Create an account, login or logout
* Browse available products
* Add products to the shopping cart and wishlist
* Delete products from the shopping cart and wishlist
* Display the shopping cart and wishlist.
* To checkout, a user must be logged in


## Added features
* Search feature with searching suggestions for any available item 
* Sort by brand, colour, price, popularity, discount or type
* Sign-in / Sign up authentication
* Pagination


## Database

### All the models can be found in the models directory created using mongoose.

#### User Schema:
* email (String)
* password (String)

#### Category Schema:
* title (String)
* slug (String)

#### Product Schema:
* Product_Id (String)
* title (String)
* imagePath (Array)
* description (String)
* price (Number)
* discount (Number)
* category (ObjectId - a reference to the category schema)



