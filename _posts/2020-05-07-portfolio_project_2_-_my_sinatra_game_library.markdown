---
layout: post
title:      "Portfolio Project #2 - My Sinatra Game Library"
date:       2020-05-07 04:01:33 +0000
permalink:  portfolio_project_2_-_my_sinatra_game_library
---


Building this Sinatra web application has been one of the most fun and challenging experiences I've had so far in software development. Even going all the way back to my high school days when I first started learning C++, I honestly don't think I'd ever been this excited to write a piece of code to create something even as mundane as a simple library to keep track of users' items. Perhaps it's the mere fact that I'm finally able to create something more than a simple CLI program or perhaps it's implementing newly acquired knowledge about more sophisticated programming and domain specific languages and having it come together into one cohesive package that has really made this project a more enjoyable learning experience. Either way, harnessing the powers of ActiveRecord, Sinatra, HTML and CSS to create a working web application has really made me very excited to keep learning more and see what else is in store. 

Obviously, this is not to say that everything about this project was fun and wonderful. As usual, I had a bit of trouble getting my program set up from scratch as I wanted to make sure that I at least had some level of understanding of the lines of code I was adding as I went along, rather than just simply cutting and pasting from similar projects and labs to get it to a working level. By delving into the details about each line of code and how each file depends and interacts with each other, it actually allowed me to get through the debugging process faster and easier this time around. 

Once the base code was set up, implementing the MVC design pattern was pretty simple. I had a pretty firm grasp of the controller routes, views, forms/inputs, models, etc. from the Learn.co curriculum as well as from online resources; and I knew from the beginning that I would utilize several models, namely User, Game and Console, that would be all associated to one another. Starting off with simple has_many / belongs_to relationships and associated functionalities, I was able to make sure that the controller routes of the application at least performed in accordance with the desired action and validation. 

As I started to expand upon the methods and features in order to get them to function more akin to how I envisioned them, I then had to rethink some of the model associations and client validations. I moved onto a has_many / has_many relationships for both the Game and Console models with respect to the User class, and with it came the use of join tables. In addition, CRUD operations had to be divided and categorized according to specific authorizations in order to ensure that no one ordinary user could impact data shared amongst the other clients of the application. 

After having met the full basic requirements of the project, I then decided to extend the application features by adding messages for validations, errors, and successful operations, in order to make the program more user-friendly and improve the flow of the user interface. I also dabbled a bit into CSS implementation as I have not really delved into that aspect of web development aside from the provided Learn.co labs and lessons. And as alot of people would probably agree, I think the best way to learn coding is to supplement the reading material and activities with one's own experimentation and exploration.

Although my Sinatra Game Library application is a relatively simple one, especially when compared to what's already out there, I think this is a solid first step into developing and getting familiar with Sinatra and seeing what more advanced languages such as Rails are capable of. It has given me the opportunity to understand the basic building blocks that make up the "magic" that these higher level languages provide so that we, as developers, can in turn focus on creating more abstract and higher functioning applications. And I, for one, cannot wait to learn more. 



