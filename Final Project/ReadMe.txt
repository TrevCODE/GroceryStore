
# Flavor Fusion

Flavor Fusion will be a website that reduces shopping time. I will be using a recipe API that will generate recipes based on what ingredients what the user likes. There will also be an option to shop in a more traditional fashion by selecting individual items. 


## Features

- User Authentication
- Firebase Integration
- Individualized Carts
- Recipe Generator
- Add to cart
- Add to Ingredient List for Recipe Generation 

 


## Startup

- Open Visual Studio Code

- Go to "file" -> "open folder"

- Open Live Server and the website will automatically open

## Pages

- There are four main pages on Flavor Fusion. Products, Recipe Generator, Account, and Cart.

- Products page will have all of the products. This is where you will add to your cart list or your fuse ingredients list. You will also be greeted with the "Recipe of the Day" which is a randomly generated recipe that is called from the API

- Recipe Generator page will have a unique list for each user based on their userId. Once the fuse button is pressed there will be an API call that links the name of the products together and returns a max of two recipies at a time.

- Account page has three states, signed in, not signed in, and register. If a user a signed in then you will see your email displayed and a logout button, If you are signed out you will be prompted to sign in or create an account. 

- Cart page fetches products from firestore based on userId and displays everything and displays it on a table. The price is also calculated as items are added and removed 