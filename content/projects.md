---
title: "Projects"
slug: "projects"
author: "Dane Williams"
---

# What I've Been Working On
I will try to update this page as I complete new projects, however the most up to date location of all my projects is of course my [github](https://github.com/danerwilliams). I also have a [gitlab](https://gitlab.com/dwilli36), but so far I only have used this for my classes at Notre Dame that submit assignments through private gitlab repos. A list of my projects in reverse chronological order is below.

## pstb.in
* December 2020
* Github: [pstb.in](https://github.com/danerwilliams/pstb.in)

This is a pastebin and url shortener I built in order to learn some serverless AWS. 
I use Lambda, API Gateway, S3 and the Chalice framework. 
There is a client available publically at [pstb.in](http://pstb.in).

## B Minor Compiler
* November 2020
* Github: (private repo)

This is a semester long project I worked on in my [Compilers and Language Design](https://www3.nd.edu/~dthain/compilerbook/) class with [Professor Thain](https://www3.nd.edu/~dthain/). 
In the class I built a 4 stage compiler consisting of a scanner, parser, pretty printer, and type checker for the B Minor programming language, a C like language specification made specifically for the class. 
The compiler was built in C and also utilizes [Flex](https://github.com/westes/flex) and [Bison](https://github.com/akimd/bison).

## Pork Chop Chat Bot
* May 2020
* Github: [pork-chop](https://github.com/danerwilliams/pork-chop)

Pork Chop is a chat bot I made which is capable of responding to specific commands such as a command for getting a stock price, as well as participation in conversation. The conversations are powered by [ChatterBot](https://github.com/gunthercox/ChatterBot) which is a conversational dialog engine that uses machine learning. My buddies and I trained the bot based on our imessage groupchat data which made things very entertaining. Pork Chop is fully modular so you can clone the repo and then train with your own data to deploy in a groupme chat of your own!

## Spidey Web Server
* April 2020
* Gitlab: (private repo)

This was my final project for [systems programming](https://www3.nd.edu/~pbui/teaching/cse.20289.sp20) which I completed with my partner [Conor Murphy](https://github.com/cnrmrphy). 
In general, the idea of this project was to build a simple http web server (like apache), using C. There is also a small part to this project called thor, which is a python script for testing the server in both single and forking mode by sending requests in parrallel. 
We have the server running on port 9898 of an AWS ec2 virtual machine we spun up and can access at [aws.danewilliams.me:9898](http://aws.danewilliams.me:9898/). 
Obviously it does not look particularly impressive from a web dev perspective as this is just an example file directory. However, the point of this project was to use low level processes in C to better understand how things like web dev project (like this website) are actually hosted on the internet. 

## danewilliams.me (this website!)
* March 2020
* Github: [danewilliams.me](https://github.com/danerwilliams/danewilliams.me)

I made this website with [hugo](https://gohugo.io/) and hosted it with [github pages](https://pages.github.com/). I highly recommend both hugo and github pages as setting this all up was stupid fast and simple.

## tmux-dracula
* March 2020
* Github: [dracula/tmux](https://github.com/dracula/tmux)

I am a huge fan of the [dracula theme](https://draculatheme.com/) and use it for vim, terminal.app, slack, and vs code. The only thing missing for me to have an all dracula set up was a theme for tmux. There are some floating around github, but most of them use powerline which I was not really interested in and I found my self unsatisfied with the options that already existed. With the extra time I had while classes are online due to COVID-19, I took it upon myself to make an all in one, plug and play tmux extension folowing the dracula color scheme! I built the extension with bash scripts that gather the information I desired to be in the status bar. I have a script for gathering the current network SSID and another script for the battery percentage and charging status which are pretty much simple Unix pipelines. Additionally, there is a script for fetching the current location from an api, and then using that information to scrape the current weather off the internet. This script runs in a wrapper that updates the weather information every 1000 seconds.  
  
UPDATE: (April 2020) I was asked to transfer my project to the dracula organization, so my theme is now official!

## PacmanRemixHLSM
* December 2019
* Github: [PacmanRemixHLSM](https://github.com/danerwilliams/PacmanRemixHLSM)

This was my final project for CSE 20221 logic design, which I took during the Fall 2019 semester with Professor Siddharth Joshi. For the project, my partner, [Billy Porter](https://github.com/billyporter), and I built a high level state machine with [verilog](https://en.wikipedia.org/wiki/Verilog), a hardware description language. Our HLSM powered a Pacman inspired game which could be played with a keyboard and displayed on a VGA.

## fisher-hall-website
* May 2019
* Github: [fisher-hall-website](https://github.com/danerwilliams/fisher-hall-website)

For the 2019-2020 school year I was appointed website commissioner for Fisher hall at Notre Dame by our hall president and vice president. I completely rebuilt the website from the ground up as an SPA in angularJS. This is the first time I have done anything with a front end before, so it was an interesting project to get introduced to HTML and CSS, which I used in addition to [Bootstrap](https://getbootstrap.com/). Moving forward Fisher's website responsibilities have been passed on to another fellow CS major in Fisher hall, [John Sullivan](https://github.com/antithalian).

## elo-tennis-predictor
* April 2019
* Github: [elo-tennis-predictor](https://github.com/danerwilliams/elo-tennis-predictor)

This was my final project for CSE 10112 Intro to Engineering II. Myself along with my group members [Billy Porter](https://github.com/billyporter), [Jamie Heneghan](https://github.com/jheneghan16), [Michael Pitz](https://github.com/mpitz1), and [Matt Dillane](https://www.linkedin.com/in/matthew-dillane-382448194/) built a [MATLAB](https://www.mathworks.com/products/matlab.html) model with a GUI which predicts [ATP tennis](https://www.atptour.com/) match results using [ELO algorithms](https://en.wikipedia.org/wiki/Elo_rating_system). Our GUI interface allowed the user to recieve betting recommendations based on the odds given by Vegas.

## EC-AR-Testing-Form
* May 2017
* Github: [EC-AR-Testing-Form](https://github.com/danerwilliams/EC-AR-Testing-Form)

This is the first real development project I have ever worked on. The goal of the project was to develop a web app which allowed students with testing accomodations at my high school to log in with their school Outlook account, and then schedule exams by filling out a form which would automatically update the test proctors Outlook calendar. I built the web app during my junior year of high school, with my only previous coding experience having been the AP Computer Science class which I took during my sophomore year through be the [TEALS](https://www.microsoft.com/en-us/teals) program at Eastside Catholic School. In hindsight, it was not well built (don't judge my code lol) as I had much to learn at the time. Probably the biggest mistake was choosing to create the app with JSP and Java, which I found appealing because Java was the only programming language I knew back then. Picking up node.js or django + python probaby would've been much more effective for interacting with REST API's and deploying to AWS in the long run.  
