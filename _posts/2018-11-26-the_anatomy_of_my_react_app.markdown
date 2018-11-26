---
layout: post
title:      "The Anatomy of My React App"
date:       2018-11-26 18:48:47 +0000
permalink:  the_anatomy_of_my_react_app
---


Hello Again! Has it been another week already? Time flies. I will use this blog to update the blog-sphere about the React App that I am building, and how to get one of your very own. As I said in my last post, if you graduated, you should not be content with your projects that you have from school. Those should be recycled for an entire set of new production-quality(Maybe not "ready") applications to showcase. I have chosen to focus on React, and build out 5 different applications using different APIs in each.  https://youtu.be/xHqYZ4GaiQI This is what it is thus far.


My first one has almost been completed. Does anyone remember in Star Wars Episode 1 when the cruiser breaks down and they have to pay pesky Sebulba to give them a part? Pesky Sebulba in our case is unemployment. This first app im building is to begin creating a storage device for all my preferred / highest level components, especially in React. NavBar, sorting graphs, fetches, you name it. It should all be on a Text Editor file with detailed separated notes. I feel this project is good. I've made various separated components that I will have to harvest into my large "parts" file. I am going to build one or two more components that I will need at a base level for my next application, and then I will harvest and call it quits on this one and retire it to the ol' resume.

The next application will then try to craft down to the nickel how I made the first. The first thing I want to be capable of doing is setting up a clone of my exact former project WITH STEP BY STEP DIRECTIONS (important), and then adding another innovative feature. I think my next app will have the ability for login and out, and be able to book travel through an API.  That's honestly not difficult given the wealth of information on React, and setting it up with Devise on the back-end with a Rails API. These will all be more goodies (fetches, data displays, authentication paradigms, etc.) to add into my little storage device. Oh... one more analogy. If someone was hiring you to work construction as a skilled construction worker, would they say don't worry, use our tools. Their hammer? Not Big Bertha? That would never happen! They expect you to have your toolbox with you when you arrive to both the interview (knock on wood it's a Hackathon format) and the first day of the job. 

Without further ado, I present my anatomy:

React: The grandaddy of them all.  What a beautiful piece of framework we all get to enjoy. Key for a project like this: KSS. Keep State Simple. Using Redux is going to capsize your time investment if you choose to make apps like this. Add Redux of course, but get a couple more standalone React Apps before. Once you master state within React, Redux begins to make 100x more sense. Redux is a scale-based framework. Don't think it's life and death. 

Netlify:  "Server" hosting for static websites like a company page, etc. This was not something we covered in Flatiron, but anytime these people say AWS experience, Docker, etc... this is the kind of thing they want to hear out of your mouth. It is a relatively simple process that I've felt, but still you need to have physically done it with proof.

Gatsby: https://www.gatsbyjs.org/ Look into this. If you haven't heard it already it is categorized as a "modern website generator", that provides a lot of the starter code that you can use to generate a site off of. The belief of using this is that you don't have to remember 50 npm installs to get something up and running. Get the Sass tables, get the starter code for a JAMstack App, and get to work.

NodeSass: Most important one by far. If you look at the video, a lot of this was my own Bootstrapping with man-made components out of CSS. This is a type of project I recommend to all because it will get you VERY comfortable with any variation of use of CSS. There is a lot of fades, zooms, enlarges, containers that were not really necesary in our school apps. 

React Helmet: Nav Bar plug-in to display in the equivalent of App.js. Uses <Link />'s to display the correct links in a favorable placing. The <Link />s can be altered in an equivalent NAV.js where the routes and destinations are available. Having said that, I may get rid of this for video background buttons. 

Overall, coming up with a individual thought rather than a YouTube walkthrough has been refreshing, and I encourage you all to try it. Find a website of a company you want to work for, and copy their website with React pageless loads and some other neat features. It's a completely valid use of your time, and you get some employment prospects out of it. I would encourage you to use the template approach, because one good build can turn into 30 great builds which is also 30 great job applications.




