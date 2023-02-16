# Live Box 
  
  ### A Live Box is a online chat based application used to connects everyone on a single platform.
  
 ![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/livebox.png) 
 
 ## UserInterface with Selected User (fixed)
   ![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/selected_public_interface.png)
   
## Deployments

     https://kkb-mmmut.github.io/Live_Box/

## Created Using
    React Js
    HTML/CSS/JSX
    JS 
    React Hooks {useEffect/useContext Api} / Routing
    Using Authentication by Firebase.
    
## Live Box
    A Live Box is an online chat based application used to connects everyone on a single platform, which will basically have the features of
     login, signup, create new chat, search users, live user interaction, send images etc. 

## Basic Features.
    1-Login page by using firebase/auth.
    2-We can create the user by using signup page.
    3-Fully working functionalty for search users and chats.
    4-Can send the messages,images or any file.
    5-Amazing user interface and awsome public interface . 
    6-Handle errors and success alerts and show appropriate Alert/Notification.
    
#  Fetching Posts
    ## In this section, we followed the following steps:
    
        1 - We created a file in the utils folder for storing constants and URLs that
        will be required when we will fetch the data.
        
        2 - Then we implemented the custom fetch function for fetching data
        from the APIs. It has 2 parameters body and customConfig.
        
        3 - Here we used the try and catch method so that the app doesn’t crash
        when an error is encountered.
        
        4 - We have used async-await syntax here with fetch.
        
        5 - An async function starts a request and returns a promise. When
        the request completes, the promise is resolved with the
        Response object. If the request fails, the promise is rejected.
        
        6 - The await keyword causes the JavaScript runtime to pause your
        code on this line, not allowing further code to execute in the
        meantime until the async function call has returned its result —
        very useful if subsequent code relies on that result! Therefore,
        the await keyword is used before the fetch function.
        
        7 - Since the body is an object and an object can’t be passed in fetch
        function. So, if it is present it is first converted into a string and then
        passed through the fetch function.
        
        8 - The response received from the firebase. 
        
        9 - For styling, we used CSS modules in which class names are scoped
        locally for avoiding naming conflicts.
        
# Firebase Authorization:  
    ## Authorization: 
    This is the most important scenario where firebase/auth is
    used. It helps to persist the user and once the user is logged in, the onAuthStateChanged
    request will include all the resources, accesses that are permitted to
    the user.
     

## Screenshots
# Public Interface
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/from_anotherside_client.png)

# User Interface 
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/client_one.png)

# Login Page 
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/login_page.png)

# Signup Page 
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/register_page.png)

# Search Results
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/Search-Results.png)

# New User Login Profile 
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/new_login.png)
 
# Overall Results
![home-page-light](https://raw.githubusercontent.com/kkb-mmmut/Live_Box/main/Screenshots%20livebox/overall_results.png) 

## How to Run the project on local server.

  1-Forked the github repository and run the project on their on deploying it.
  
  2-Download the project on you local computer and unzip the file.
  
  3-Then download all the dependencies by using "npm install".
  
  4-Start the project by using "npm start".

## Happy Hacking !!
