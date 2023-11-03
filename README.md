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
