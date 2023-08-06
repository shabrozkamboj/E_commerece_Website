This is the clone of an E_commerce website known as [SHOPPERS STOP](https://www.shoppersstop.com). 

## Basic inference about the company

Shoppers Stop is an Indian department store chain, owned by the K Raheja Corp. There are 86 stores across 40 cities in India, with clothing, accessories, handbags, shoes, jewellery, fragrances, cosmetics, health and beauty products, home furnishing, and decor products.

##Demo
<img width="608" alt="image" src="https://github.com/shabrozkamboj/E_commerece_Website/assets/98809822/ae81bb13-99de-4bc2-98f8-2ac742c67556">

<img width="607" alt="image" src="https://github.com/shabrozkamboj/E_commerece_Website/assets/98809822/5c5334ab-103d-4cb5-a635-b16a281fdf19">

<img width="608" alt="image" src="https://github.com/shabrozkamboj/E_commerece_Website/assets/98809822/65a9e3c7-ba65-48ca-a3de-f8c8f9a60a10">

<img width="608" alt="image" src="https://github.com/shabrozkamboj/E_commerece_Website/assets/98809822/e11103f2-91f2-4cb7-98df-f330fdb98e28">

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



