---
layout: post
title:      "React / Rails / Webpack "
date:       2018-12-26 11:38:30 +0000
permalink:  react_rails_webpack
---


As I delve further into React and it’s use cases for front-end development, I usually have seen two ways to use it. Encompassed within Webpack, which for us from rails will feel comfortable. The next, our final project, was front-end and back-end. This uses create-react-app, which comes with a lot less headache in terms of configuration. 

I am making an e-commerce application for my second React-a-thon, and this is using WebPack and rails. Instead of initializing rails as an API, you can instead use regular rails, and embed React into the project. I feel like this type of project has some pretty set out pros and cons that I will get into as I am facing them right now, and they may be subject to change once I have actually completed the project: 

React – Rails - WebPack
Pros 
•	Great starter code – Lots of GitHubs willing to provide their boiler plates for how to make a webpack react-rails project. I got to choose from a couple. 
•	More rails! – ERB tags are more important
•	Open Source – A lot of people use webpack, and every error I have gotten that doesn’t make sense has an explanation online, which is very helpful 
  Cons
•	Eslint – For some reason eslint becomes a mean mean devil when combined with WebPack. If the application can’t start for indentations or using var instad of let; just not a good use of one’s time to have to fix those up. The create-react-app isn’t cluttered with syntax packages. 
•	Rails API – It’s a good tool! Especially when you aren’t using rails for views, it felt like a clearer choice, especially when I needed my app to fetch newly routed API data from the app anyway 
•	Webpack breaks – There have been times where I can’t refresh my webpack so my app will always interpret the stuff before I saved 


So far, I wouldn’t use webpack again. It’s annoying to have to do more than what you have to do with the API version, all for what? Nothing really. The front-end-back-end version CSS is more intuitive, the apps routing becomes clear (I have a show page and a JSON route for the show page) if you separate concerns on front-back entirely, not just a little bit. Sure, rails side felt a lot more attainable to the front end, and I was very surprised I could just spin up JSON data on another route within the same app. 

It becomes more apparent to me each time I make a new project just as to why rails and react were the choices Flatiron made for us all to learn. It really is a no brainer when pretty much an entire full-stack app is written for you when you connect the two pieces together, and all you had to write was a couple command lines to get it up and running . 

I will still see this webpack project through,  and deliver something neat in my opinion. With all environments, once you feel comfortable things start to come easier. I am still no genius with Webpack, but I know where to go if something goes wrong. I would suggest you all start incorporating as much different technology with your stacks as possible, as employers will randomly ask you if you have experience in something you don’t really have a reason to know, except for the fact that some guy with a job had an off chance of asking you. 

