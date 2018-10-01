---
layout: post
title:      "Fetch and Promises "
date:       2018-10-01 17:14:33 +0000
permalink:  fetch_and_promises
---



I wanted to look back on two different components of my React project, and why each one is so important when it comes to the functionality of React. 

Fetch 

Fetch is the "how" portion in the equation of requesting data from an API, which is usually in JSON.  The server will then respond with a Javascript promise saying that they will send the data once it has been completed, therefore allowing our interpreter to give us more time to complete other essential functions in the application. When it is done, the server will then give us our data back, and in the specifications that we made in the request.

Value 

The reason fetch(and the advent of Javascript promises) is so useful in React is because we can pull in and store data in different components, and then display them in larger parent components, or put it into the app itself. This division keeps features clearly separated, and each fetch is designed for a specific purpose. 

Pre-requisites 

Construct 
In order to fetch, we will need to use 3 lifecycle methods that can get us from start to finish with a Fetch request. The Constructor method is going to be the first, where we will usually pass props from the parent to child through super(). The next portion is setting the state. This prepares Javascript for the new data, and gives it the proper holding place (whether it’s a string, array, etc. that is expected back to us). 

Prepare 
Step 1
The next stop is a “will” lifecycle method, that comes before something happens, and did is after. The will component will be the promise that can be fulfilled later on. 
Step 2 
Create a fetch. This is going to be a simple request to an API, which is a link. The fetch request gets a lot of credit for things that are done by other, supporting functions
Step 3 
The use of “.then” to specify how the data is returned, and what data we would like. We would use an iterator of “.map” or a for loop to satisfy this. 
Step 4 
Key and return data. Using Keys helps React understand how the data is going to mapped over. Within the key, you can specify what type of data you’d like posted (img, p, h1,h2).


Update 
The final portion is setting state with the updated data. We are telling React we have new information, and we would like the state updated to reflect that. 


As we can see here, React was built for speed. We don’t want to spend time on functions that haven’t cooked yet, and we also want to speed up the linking process by making sure that we have everything we need before bothering any APIs. 

