---
published: true
title: Starting out. 
layout: post
---
Step one:

rails new crowdfund

Creates all the things. 

go to localhost/projects which will be the index page. 
No route exists, head to routes.rb delete all the commented crap and write :

verb "url" => "name_of_controller#name_of_action"

AKA

get "projects" => "projects#index"