---
title: Web Component Framework Breakdown.
description: Different JS Frameworks for development.
date: 2021-09-12
tags:
  - Web-Component
  - JavaScript
  - node
layout: layouts/post.njk
---
This week in my Web Components class, we looked into 4 popular Web Component Frameworks: Angular, React, StencilJS, and VueJS.  Each group member took one framework and followed the boilerplate/"Hello World" example to understand how projects in these frameworks are structured.  Below I will show the results of our research and testing as well as providing my personal opinions on a framework I would use.
 
Across all four frameworks, there were some similarities to the way they worked.  All four use JavaScript to create/define their components as well as the interactions with them.  Stencil JS does use TypeScript files however TypeScript is then translated to JavaScript.  The frameworks also have a similar file structure in a sense that each component is given it's own directory to be defined within the project.  What is in these directories varies by project.  Most use a JavaScript function and returns that return HTML but VueJS uses.Vue Files instead.  Lastly, all of these frameworks have a base index.html file which is where all the custom components are added to/called.
 
Based on looking at these frameworks, I think VueJS has the easiest development experience because it has the fewest amount of files out of all four frameworks.  I found when looking at the boilerplates for these frameworks, I easily understood where everything was in the VueJS directory.  I did not need to dig very far to find where the custom component was defined and what files interacted with it.  Since I have not used it to build anything, I don't know if can efficiently handle interactions like in other frameworks.  I have heard of React and Angular from my previous internships, but I have not heard of VueJS before.  This leads me to wonder how vast the development community is.
 
With a few finds from our research, I would probably work with React to build an application.  I know from personal experience that the react community is vast.  The JavaScript files declaring components looks like HTML and is easy to understand what the code does.  I also can easily follow the file structure of this project, there are more files than VueJS, but it is still easy to follow along.
 
To view the boilerplates my group generated, please visit our GitHub Repo here: https://github.com/3B4B/boilerplates