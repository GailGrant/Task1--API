# Task1--API
Task 1 is based on testing the API. I used the HTTP Methods to perform the API request in Postman and i also used asseritions to perfom
verification. 

# Publish Link
Postman allows you to publish your work when you are done so i also published my collections. Below its the link that will direct you to my 
collections for Task 1.
https://documenter.getpostman.com/view/5952302/RzfZMsJq

# Test Results
The test results can be downloaded from Postman and they are stored in a JSON file that i have provided. In order to read JSON file i used
Newman (is the npm package of Postman, it allows us to view us to view a JSON file in an HTML format which is more clear that JSON format)

# How to use Newman

1. Install latest version of Node (Node.js)  in the computer 


2. Set the path of Node Bin Folder in the Computer path Variable.


3. Open the cmd and type following command "npm install -g Newman”. It will install Newman in the PC. 


4. Postman provides a feature to download the collection as JSON Data.


5. Download the collection from the Postman


6. Open the command window in the downloaded path of collection and type following Command "newman -c CollectionName.json – H Reports.html"
Observe the Command window in the Postman


7. Observe the Reports.html in the same Directory 
To view the output JSON data of API  , modify  the command as "newman -c CollectionName.json  -O output.json – H Reports.html
