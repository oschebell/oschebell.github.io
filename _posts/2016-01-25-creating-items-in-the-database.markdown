---
published: true
title: Creating items in the database
layout: post
---
So now we have the done the migration and have the database setup we can fill the fields with actual items. 
In this case we can create a variable 'project' and  call the ruby class Project and the method .new

Like:

project = Project.new

This will create a new item in the database will attributes set to 'nil'.

From here we can assign values to each of the database fields by calling the project variable. 

project.name = "Electric Skateboard"

project.description = "A brand new ultra light lithium battery powered skateboard"

project.target_pledge_amount = 10000


We can also do this as one move with project = Project.new(name:'Meat Popsicle', description:'Negative, I am a meat popsicle', target_pledge_amount:20)

project.save