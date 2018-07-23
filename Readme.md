## go get me some api keys! 

Api keys make programmers feel like worthy programmers with secure applications. 
<br/>But ohhhh my gosh they are a pain for users to set up. 


## what people are saying, 
"lastPass but for environment variables" -ryan murphy 😜

## how it will work...
1) All the user will have to do is create an account with a username and password and then run this application.

2) Developers will 
<br/>submit pr's with information for making requests to their websites using authentication to gather the api key.

3) The application will have a cli that will allow the user to select from a list of compliant applications.


This application will contact the website get the api key and store it in an environment variable. Then if they run the command in a particular project it will assign that api key in the correct location automatically!

## additional information...
This application may need to support usage of multiple api keys. 
1) Therefore the keys may be stored in an object ordered sequentially 
2) or an api key array.
