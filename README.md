# rn-assignment6-11047613

In the project, I split up both the Cart Screen and the Home Screen into parts to help me easily identify and rectify errors when they occur. 

# Home Screen
The Home Screen consists of the Header, OurStory, Products and HomeScreen javascript files.
## Header.js
The Header.js file contains the code for the header of the Home Screen. It contains the menu, logo, search and shopping bag icons.
## OurStory.js
This file contains the text 'OUR STORY' as in the UI mockup, the ListView and Filter icons.
## Products.js
This file contains the list of products in the app.
## HomeScreen.js
This file is just the compilation of all the other files. It makes up the actual home screen.


# Cart Screen
I programmed the shopping bag icon on the Home Screen to take me to the cart screen since it was the closest thing from the icons provided in the assets folder of the google drive that represented a checkout section. 

The Cart Screen consists of the Header, Checkout, Footer and CartScreen javascript files.
## Header.js
The Header.js file contains the code for the header of the Cart Screen. It contains the logo(which also serves as a navigation since there was no back button), search, the page title text('CHECKOUT'), and an image of a border I created myself to mimic the border in the UI mockup.
## Checkout.js
This renders the items in the Home Screen so when products are added to cart from the home screen, they appear on the cart screen. it also allows a user to delete items from the cart screen.
## Footer.js
This file contains the checkout button, and displays the estimated sum of the products added to the cart screen
## CartScreen.js
This file is the compilation of all the other files in the CartScreen folder to form the actual cart screen.
## CartContext.js
In CartContext.js, I utilized React's Context API and useReducer hook to handle the cart Screen's state. I used AsyncStorage to store and retrieve the data in the cart in such a way that even if the app is closed and opened again later on, the items added to the cart will still be in the cart

# Overview(Summary)
This app is wired in such a way that the Home Screen displays a list of available products that can be added to cart. The Cart Screen displays the items that have been added to cart from the Home Screen. The products in the cart screen can be removed. Below are screenshots of the app:

## Screenshots of the App


![Screenshot (255)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/edb4165c-eb85-4070-9317-727bf3bc9002)




![Screenshot (256)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/9d8777fe-6e39-4adc-aff8-d634d1d049e7)




![Screenshot (257)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/c005e843-c405-464b-9b95-1adef938ab30)




![Screenshot (258)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/f707cab8-5ed8-4f15-85a4-76b86a61aa1a)





![Screenshot (259)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/437e6a4d-dafd-4b42-a74f-99217ca97c77)



![Screenshot (260)](https://github.com/JD-2104/rn-assignment6-11047613/assets/151099828/6159f5ae-50ad-4128-9f24-89e851bd9441)


