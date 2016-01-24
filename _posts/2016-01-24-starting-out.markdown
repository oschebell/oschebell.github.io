---
published: true
title: Starting out. 
layout: post
---
Step one:

rails new crowdfund

Creates all the things. 

 - Go to localhost/projects which will be the index page. 
No route exists, head to routes.rb delete all the commented crap and write :

verb "url" => "name_of_controller#name_of_action"

AKA

get "projects" => "projects#index"

Then we have a projects controller error:

 - Go to terminal rails g controller projects

Now we have action 'index' error for ProjectsController. Sweet another error! 

- Add 
          def index
          end

-Refresh, now missing template error. Awesome. 
-Go to Views, Projects and create in index.html.erb