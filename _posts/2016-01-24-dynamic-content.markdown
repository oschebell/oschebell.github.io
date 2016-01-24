---
published: true
title: Dynamic Content
layout: post
---
Cool so we have a view showing html content but we want it to show dynamic content. 

So in the Projects Controller we will make an array of projects like so:

@projects = ['Electric Skateboard', 'Meat Popsicle', 'Waterproof Teabag']

Then in the index.html.erb we can call this with 
<%= @projects %>