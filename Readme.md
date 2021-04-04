##Initial SpringBoot CRUD API with MySQL

#####This project contains a simple SpringBoot API with MySQL. Here, I used simple Product based API to accomplish the basic CRUD functions.

######To complete this project I used IntelliJ IDEA integrated development environment.

######STEP 1 - Clone the project into your computer
>Repository Link : https://github.com/rusiruavb/Inital-Spring-App.git

######STEP 2 -  Open the project in the IntelliJ IDEA

######STEP 3 - Configure the necessary changes in the project
> Add necessary database changes into the application.properties file.
> Install the Mervin dependencies. 

######STEP 4 - Run the project

####API End Points

#####Create New Product : (POST) - http://localhost:9090/addProduct
> Request Body
> ```
> {
>   "name": "iPhone 5s",
>   "price": 15000,
>   "quantity": 120
> }
> ```
#####Create List of Products : (POST) - http://localhost:9090/addproducts
> Request Body
> ```
> [
>   {
>       "name": "iPhone 5s",
>       "price": 15000,
>       "quantity": 120
>   },
>   {
>       "name": "Samsung S7",
>       "price": 27000,
>       "quantity": 52
>   }
> ]
> ```
#####Get All Products : (GET) - http://localhost:9090/getallproducts
#####Get Product By Id : (GET) - http://localhost:9090/get/id_of_the_product
#####Update Product : (PUT) - http://localhost:9090/update
> Request Body
> ```
> {
>   "id": 1
>   "name": "iPhone 5s",
>   "price": 15000,
>   "quantity": 120
> }
> ```
#####Delete Product By Id : (DELETE) - http://localhost:9090/delete/id_of_the_product