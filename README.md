# MERN Stack Ecommerce (Travel App)

## Live Project: https://merntravelecommerce.herokuapp.com/

To use this application, 

1. make dev.js file inside config folder 
2. put mongoDB info into dev.js file 
3. Type  " npm install " inside the root directory  ( Download Server Dependencies ) 
4. Type " npm install " inside the client directory ( Download Front-end Dependencies )


To solve the image upload problem,

1. Make sure you have an uploads folder in the root directory of your project.
2. Make sure the uploads folder is not included inside .gitignore
3. Add an empty file named .gitkeep in the uploads folder so that git doesn't ignore the empty folder.
4. After running heroku create and creating the app copy it's URL,  you can find the URL of your app at settings tab,  scroll down to domains you will find your app's URL copy that.
5. Replace the URL http://localhost:5000 with your app's URL that you have copied earlier and paste them in those files:
   client/src/componensts/utils/FileUploads.js
   client/src/componensts/utils/ImageSlider.js
   client/src/componensts/views/DetailProductPage/Sections/ProductImage.js
   client/src/componensts/views/CartPage/Sections/UserCardBlock
