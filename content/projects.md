---
title: "Projects"
slug: "projects"
author: "Dane Williams"
---

# What I've Been Working On
I will try to update this page as I complete new projects, however the most up to date location of all my projects is of course my [github](https://github.com/danerwilliams).

## Hierarchical Sankey
* June 2021
* Blog: [Published my first academic research paper!](/posts/published-my-first-academic-research-paper/)
* Repo: [billyporter/hierarchical-sankey](https://github.com/billyporter/hierarchical-sankey)

At Notre Dame I am member of Professor Chaoli Wang's [Data Visualization lab](https://sites.nd.edu/chaoli-wang/team/).
As part of research on sankey diagrams, we developed visual analytics tools for [ND Learning](https://learning.nd.edu/). 
The result is a few novel hierarchical sankey diagrams which we created using [D3.js](https://d3js.org/), a popular visualization library for JavaScript.
You can view the deployment of our visualizations [here](https://fwr008wy2p.pstb.in/src/combined/index.html).

## playruski.com
* May 2021
* Blog: [Introducing playruski.com](/posts/introducing-play-ruski/)
* Repo: [coderQuad/ruski](https://github.com/coderquad/ruski)

This is a full stack web app that my friends at Notre Dame and I built using a [Angular](https://angular.io/) / [GraphQL](https://graphql.org/) / [Node.js](https://nodejs.org/en/) tech stack.
The app allows users to log games of ruski, which is a popular sport at the [University of Notre Dame](https://nd.edu/), particularly among the men of [Fisher Hall](https://fisher.nd.edu/#/).
Users are then ranked using a variation of the [Elo algorithm](https://en.wikipedia.org/wiki/Elo_rating_system).

## pstb.in
* December 2020
* Blog: [Paste bin with serverless AWS](/posts/pastebin-with-serverless-aws/)
* Repo: [pstb.in](https://github.com/danerwilliams/pstb.in)

This is a pastebin and url shortener I built in order to learn some serverless AWS. 
I use Lambda, API Gateway, S3 and the Chalice framework. 
There is a client available publically at [pstb.in](http://pstb.in).

## B Minor Compiler
* November 2020
* Repo: (private repo)

This is a semester long project I worked on in my [Compilers and Language Design](https://www3.nd.edu/~dthain/compilerbook/) class with [Professor Thain](https://www3.nd.edu/~dthain/). 
In the class I built a 4 stage compiler consisting of a scanner, parser, pretty printer, and type checker for the B Minor programming language, a C like language specification made specifically for the class. 
The compiler was built in C and also utilizes [Flex](https://github.com/westes/flex) and [Bison](https://github.com/akimd/bison).

## Pork Chop Chat Bot
* May 2020
* Blog: [Building an AI chat bot](/posts/building-an-ai-chat-bot/)
* Repo: [pork-chop](https://github.com/danerwilliams/pork-chop)

Pork Chop is a chat bot I made which is capable of responding to specific commands such as a command for getting a stock price, as well as participation in conversation. The conversations are powered by [ChatterBot](https://github.com/gunthercox/ChatterBot) which is a conversational dialog engine that uses machine learning. My buddies and I trained the bot based on our imessage groupchat data which made things very entertaining. Pork Chop is fully modular so you can clone the repo and then train with your own data to deploy in a groupme chat of your own!

## danewilliams.me (this website!)
* March 2020
* Blog: [Hugo tutorial](/posts/hugo-tutorial/)
* Repo: [danewilliams.me](https://github.com/danerwilliams/danewilliams.me)

I made this website with [hugo](https://gohugo.io/) and hosted it with [github pages](https://pages.github.com/). I highly recommend both hugo and github pages as setting this all up was stupid fast and simple.

## tmux-dracula
* March 2020
* Blog: [My first open source contribution](/posts/my-first-open-source-contribution/)
* Repo: [dracula/tmux](https://github.com/dracula/tmux)

I am a huge fan of the [dracula theme](https://draculatheme.com/) and use it for vim, terminal.app, slack, and vs code. The only thing missing for me to have an all dracula set up was a theme for tmux. There are some floating around github, but most of them use powerline which I was not really interested in and I found my self unsatisfied with the options that already existed. With the extra time I had while classes are online due to COVID-19, I took it upon myself to make an all in one, plug and play tmux extension folowing the dracula color scheme! I built the extension with bash scripts that gather the information I desired to be in the status bar. I have a script for gathering the current network SSID and another script for the battery percentage and charging status which are pretty much simple Unix pipelines. Additionally, there is a script for fetching the current location from an api, and then using that information to scrape the current weather off the internet. This script runs in a wrapper that updates the weather information every 1000 seconds.  
  
UPDATE: (April 2020) I was asked to transfer my project to the dracula organization, so my theme is now official!

## fisher-hall-website
* May 2019
* Repo: [fisher-hall-website](https://github.com/danerwilliams/fisher-hall-website)

For the 2019-2020 school year I was appointed website commissioner for Fisher hall at Notre Dame by our hall president and vice president. I completely rebuilt the website from the ground up as an SPA in AngularJS. This is the first time I have done anything with a front end before, so it was an interesting project to get introduced to HTML and CSS, which I used in addition to [Bootstrap](https://getbootstrap.com/). Moving forward Fisher's website responsibilities have been passed on to another fellow CS major in Fisher hall, [John Sullivan](https://github.com/antithalian).
