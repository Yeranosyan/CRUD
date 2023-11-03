# CRUD Operations with Node.js and Express, Gagik Yeranosyan 2023

## Open a New Terminal from the top menu. Test an endpoint to retrieve these users
- curl localhost:5000/user

## Check the output of the GET request using the curl command
- curl localhost:5000/user/

## View the output for the user with mail id johnsmith@gamil.com
- curl localhost:5000/user/johnsmith@gamil.com

## To post a new user with mail id
- curl --request POST 'localhost:5000/user?firstName=Jon&lastName=Lovato&email=jonlovato@theworld.com&DOB=10/10/1995'

## To verify if the user with email 'jonlovato@theworld.com' has been added, you can send a GET request
- curl localhost:5000/user/jonlovato@theworld.com

## Use the below command to update the DOB as 1/1/1971 for the user with mail id 'johnsmith@gamil.com'
- curl --request PUT 'localhost:5000/user/johnsmith@gamil.com?DOB=1/1/1971'

## To verify if the DOB of the user with email 'johnsmith@gamil.com' has been updated
- curl localhost:5000/user/johnsmith@gamil.com

## Use the below command to delete the user with mail id 'johnsmith@gamil.com'
-curl --request DELETE 'localhost:5000/user/johnsmith@gamil.com'

![POST](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/0a05f02e-b81a-4d03-a3a7-c450cfd9635d)
![GET](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/c45d3ca5-ff39-4d3a-a9a2-0422fb279881)
![GET by ID](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/d550a0e9-7c51-4976-8c53-27b66d1aebe2)![add user](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/d5e925ba-7b23-4e01-ad66-d3894a46fc6b)
![add user checks](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/59e525da-38ab-4b0c-8ad4-4cd9d1420e75)![PUT request](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/f0c3adfc-a9d6-4b53-a53d-baf49501f396)
![DELETE](https://github.com/Yeranosyan/CRUD-Operations-with-Node.js-and-Express/assets/120154377/c48d3f0c-1af0-4379-8884-b7e28f3073af)




