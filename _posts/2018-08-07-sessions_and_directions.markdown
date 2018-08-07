---
layout: post
title:      "Sessions and Directions"
date:       2018-08-07 15:26:30 -0400
permalink:  sessions_and_directions
---


The two topics that I have decided to dig deeper on would be both the session, and deeper information on what our controller methods do when they direct us via "erb", or via redirect. Even though I have begun to learn and understand rails, I think that clarifying these two topics are extremely important when trying to both understand the car, and what's behind the hood. The session is what makes our application unique in nature from one visitor to the next, and the directions we implement in our controller are crucial in understanding what different functionalities we get when we choose one or the other.


Sessions. This was a topic that we covered during our later portions in Sinatra education. What stuck out to me in my further research was how it related so similarly to "cookies" that we encounter every day during our web visitations. A cookie put simply is a ***hash*** to store information in. That information stored in one request can be used during later requests. An example from my project was the application controller functions logged_in? and current_kennel. These were probably the two most heavily used functions to make sure that each and every request was being lined up with the correct kennel/user. Most of my functions started with "if logged_in?", so that there would always be a fail safe to line up the kennel_id that was set in the beginning of the session was the same as the one making the request. 

In my application, whether you were signing up or signing in, setting a session to a kennel_id was crucial in my controller. That session was holding the information that allowed the seamless use of the application, and giving the user an individualized experience. A key component between a static vs. dynamic site.


The other topic in my application that I wanted more clarity on was rendering vs. redirecting. The render function is useful where you don't need a completely new request. In my code "get /greyhound/:id" is a perfect example of how when the id is found, all it has to do is render the page with the existing information given to it (ID!). The else conditional needs new information, thus needing a new http request via a redirect. 

The sections of this course that I enjoy the most are the analogies. The MVC = restaurant analogy was one that has helped me move my brain into the code a lot smoother. So, keeping in the analogy, there are certainly ways that I can conceptualize these topics within the restaurant. The session is the table number. Without the table number, the staff (i.e the controller/waiter and model/chef) wouldn't know what to give them or where to go. A rendering is following-up on an existing order ("here are your steak fries!"), where as a re-direct is making a new order ("can I have some steak fries too?").

The little topics are often most fun. Building the house is only as fun as getting decorate the insides. I feel like these two components of Sinatra are what can grow into unique things. For example, sessions have opened my mind to what the possibilites of a cookie are. What can be stored? How can adding things to a session hash create so much value for companies like Amazon/Facebook? Clearly a session[:kennel_id] = @kennel.id just scratches the surface to what is possible inside of a session hash. 






