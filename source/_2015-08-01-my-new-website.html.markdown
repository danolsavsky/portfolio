---
title: My New Website
date: 2015-08-01
tags: example
layout: article
---

It had been quite a while since I lasted updated my website so it was time for an update. 

Requirement Review
Tracking down a business stakeholder on this project was easy, it was me. Using one of my own stakeholder interview templates, I was able to extract the information I needed to get started. The purpose of my new website is to serve as an online portfolio for job recruiters and potential employers. In addition, I am going to use my portfolio to continue to build a sphere of influence as a thought leader in the UX/UI industry. To accomplish these goals, I will need to include an area to introduce myself, display my work, keep my journal, host my resume, and provide my contact information -In that order. Simple!

Evaluation
My next step was evaluating my current website. It had been about six years since my last design, that's a long time in the tech world. My last style was skeuomorphic and minimalistic -That was in at the time. I wanted to update the design to use a flat style. That's what's in now.

Upon further inspection, I liked the placement of the work examples and the blog articles. However, I think by removing the JavaScript slider and just listing all of the projects is a more efficient approach to viewing my body of work -People can 'skim' it. One thing that was missing from the old design was a downloadable resume. Recruiters and hiring managers always ask for a resume, usually in a PDF format... Need to add that for sure. The old design is also missing a photo. Including a photograph of myself will make a bigger emotional impact on peers and potential employers. Finally, I wanted to keep the social media icons that were there but add SlideShare, Twitter, and GitHub.

Market Review
Once the evaluation was complete, I took a look at how some of my peers were presenting their work. I found several sites that I liked for their simplicity and exemplary demonstration of skills. I took screenshots of each site and identified what I liked about them.

Personas
Next, I developed three personas that represented the three different user types that I expect to visit my site; Job Recruiters, Hiring Managers, and Peers. 

Style Tile
To define the look and feel of the website I created a style tile. Style tiles are a great way to communicate the visual language of the website (colors, fonts, icons, etc.) without investing time into high-fidelity Photoshop mockups. Style tiles can also include a preview of actual interface elements without having to define the entire layout. 

Choosing a UI Framework
To save time on front end development, I decided to use a UI framework. I am most familar with Bootstrap however I also looked into Semantic UI, Foundation, and UIkit. After evaluating my options, I chose to stick with Bootstrap as it's still the most popular and mature option.

Working with Middleman
I had a small list of technical requirments to start with so I had many choices for development frameworks. I wanted a framework that I am familiar with, that has a good support community, and that is well-suited for blogging. My initial thought was WordPress but I decided against it thinking that it's too robust. All that code and database administration for one little blog, eshh! I dont need a GUI to publish content either. 

After searching online for additional blogging platforms, I discovered Middleman. Middleman is a static site generator that's is built on Ruby and uses the RubyGems package manager for installation. Middleman has an official extension to support blogging too. So far so good! Some of the additional benefits of using Middleman include; 

* Setting up a new project takes little effort
* The development cycle is simple
* The use of partials to reduce code duplication (DRY code)
* Using SASS and CoffeeScript to reduce the amount of code
* Automatically compresses JS and CSS on build to reduce the file size footprint
* It's easy to deploy to Heroku via GitHub
* Pretty URL's help make a site look more mature
* Ruby helpers [drops mic]


Google Analytics
I am interested in learning more about how users interact with my website so I setup Google Analytics. The statistics that I monitor the most often are the number of visits, popular pages, exit points, the bouce rate, the technology used to view the site, time spent on the site, locations, and traffic referral source. It's not trivial! From my dashboard reports, I can extract the data points that I need to learn more about my users behaviors while using my site. From there, I can start to make adjustments and test again. 

A/B Testing
For advanced analysis, I setup Optimizely on my website and funnled users into one of three different website themes. My goal was to learn what colors and layouts are the most engaging. So far, I've had mixed results. I believe, based on my user groups, that recruiters are looking for my resume, peers are looking for my journal, and hiring managers are looking at my work. The traffic and engagement are be split among these three areas and layouts. This does however provide validation for my personas,


