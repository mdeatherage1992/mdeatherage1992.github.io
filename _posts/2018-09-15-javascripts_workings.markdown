---
layout: post
title:      "Javascripts Workings "
date:       2018-09-15 12:36:56 -0400
permalink:  javascripts_workings
---


As we approached the fusion of Rails and Javascript, I am sure many of you were like me in irrational frustration. As a new developer, I was becoming quite accustomed to simplicity of Ruby and Rails. Built for the human being, Rails' Gems, online community, and logical syntax were easy to use and understand. 

Then Javascript. Although I had taken a Bootcamp Prep on Javascript, it barely scratched the surface on what there was to learn on the language and it's use in web development. As I "saturated" myself in the job market, I noticed the company's that were interested in me were focused on what I knew in React. Angujar, React, Node, Vue were all the frameworks that employers were willing to look beyond my lack of experience and talk to me. Did I embarass myself at their questions? OF COURSE. But, I learned how important it is to be using frameworks like AJAX, JQuery, as riding the bike without the training wheels teaches one to understand the bike, and subsequently the external things that can support them. 

The parts of the bike that I had trouble with during my project were Hoisting, Scope, Context, and the advent of ES6. As I have learned, its quite common to be stuck with these as one transfers Ruby based education into Javascript. The page becomes littered with brackets and foreign syntax, which then confuses how things are initialized, declared, and outputted. 

**Hoisting** - 

Javascript's unique behavior is showcased with declarations being put into memory before any code execution takes place. That means that a function could be called in code space before the function itself, and the function would still render. Initializations however (Var A = 2;), are not put into memory beforehand. If using Var, the variable is, but the value of the variable is not, thus making it undefined. Using Let and Const, however, are not hoisted into memory before execution, and will return "not defined", rather than "undefined". The way I conceptualize this is that undefined is 50% of a variable (Var A;)  and not defined has nothing to go on prior to to execution. 

**Scope**
Scope is created in Javascript only by functions. Conditional statements do not create new scopes, and the rule of new function = new scope can be applied. These functions also have access to those that were declared before it.  As conditions and functions begin to pile up on a page, knowing what relationship each function has what information; adding complexity becomes easier. The scope chain is the concept that helped me hammer down this knowledge. Any function that is defined within a function has a local scope that has access to the outer functions scope, thus creating a link in the chain.The scope chain is a road map into where Javascript looks for things that are defined/declared. It will dig a hole to the inner most scope, and search outwards.  As I begin to conceptualize that, I understand the true masters of these languages would use scope to artistic advantage. 

**Context and This**
the concept of this, for myself, feels like a Ruby "super SELF". The use of "this" can be defined in different ways depending on how it's used. The use of self in a regular inspect in the Google Chrome console yield you the "global object" called window, which I would encourage you take a look at. It's a large object of property/value pairs, some of which are interesting to poke around in! The other ways that this can be defined and their differences, lies with how the context is applied. If using .Call or .Apply, two methods provided to all functions in JS through function.prototype, you can shift context of this into what is applied. Binding the context, however, gives the added mobility to call the function when useful, and keep the original context, when .bind was called. I think of it as freezing the time period and re-testing it. 

**ES6**
I think alot of us have had the luxury of working with the most recent updates to software, thus not knowing how good we have it. The properties discussed above, especially the use of let,var, and const, are what can help further the development of loadless websites and applications. Some bullets on ES6: 

•	Babeljs.io to transpile into html friendly format for web display
•	Block scoping with let. Only available in the next enclosing block. In Strict mode
•	Const turns variables into constants, and cannot be changed
•	Arrow functions function(n)  for (n => X)
•	Find array method (VERY RUBY LIKE) arr.find(n => n > 32)
•	Destructuring. Swap values inside a and b without using extra variables
•	Object declaration with just keys name = {key,key,key} rather than key value say with ‘let’

**Conclusion**

I am no expert at Javascript, and it's use cases. I think with a new-ish language to learn at this time in the course, one has to learn the rules of the playground before being able to really use the equipment available. The better conceptualized the rules are, the more creative the ideas can be using those rules for entrepreneurship // innovation // success.


