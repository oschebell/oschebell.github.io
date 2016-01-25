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