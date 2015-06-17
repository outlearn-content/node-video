<!--
{
"name" : "node-video-series",
"version" : "0.0.1",
"title" : "Node.js with Express.js and MongoDB",
"description" : This is a series of videos about using Node.js with Express.js and MongoDB.",
"homepage" : "https://www.youtube.com/user/learncodeacademy",
"author" : "LearnCode.academy",
"freshnessDate" : 2014-04-20,
"license" : "Standard Youtube License"
}
-->


<!-- @section -->

# What is Node.js Exactly? - a beginners introduction to Nodejs

<iframe width="560" height="315" src="https://www.youtube.com/embed/pU9Q6oiQNd0" frameborder="0" allowfullscreen></iframe>

What exactly is node.js? Is it a command-line tool, a language, the same thing as Ruby on Rails, a cure for cancer?

If you're new to web development, it can be a bit confusing as to what exactly node.js is and to what you should do with it, and there's a lot of information out there...most of which seems to be tailored towards genius-level developers.

So, here's a node.js introduction for those who have no idea what it is.

We're going to cover the difference between javascript in a browser vs javascript in node.js and the common uses for node.js.

To wrap it up, we're going to spin up a quick web server in node.js just to show you how easy it is.

<!-- @section -->

# Node.js tutorial for beginners 2014 - an introduction to Node.js with Express.js


<iframe width="560" height="315" src="https://www.youtube.com/embed/FqMIyTH9wSg" frameborder="0" allowfullscreen></iframe>

This video is an introduction to Node js using the latest updates to the Express.js framework. Nodejs is an amazing web framework that makes web development and engineering tons of fun.

<!-- @section -->

# Node.js MongoDB Tutorial using Mongoose

<iframe width="560" height="315" src="https://www.youtube.com/embed/5e1NEdfs4is" frameborder="0" allowfullscreen></iframe>

This tutorial covers how to work with a MongoDB database using Node.js, Express.js, & Mongoose.

Node.js and MongoDB are simply made for each other. Mongoose is an awesome tool for managing connection, schema, document relations, getting, setting, and more.

This code is on Plunkr!: http://plnkr.co/edit/E5OpHJzVM9RsgVnbqhvp?p=catalogue

The first step in this Node.js Mongoose tutorial is to install Mongoose and make a connection to the MongoDB database. Then, we can easily register models, which can be called in any route to access collections from the mongo database.

Using the Express.js framework for this makes the whole process extremely nimble and light as well.

<!-- @section -->

# Nginx Tutorial - Proxy to Express Application, Load Balancer, Static Cache File

<iframe width="560" height="315" src="https://www.youtube.com/embed/FJrs0Ar9asY" frameborder="0" allowfullscreen></iframe>

Nginx ROCKS! In this Nginx Tutorial, we're going to setup Nginx to receive http requests to our domain name (port 80), then proxy to our Express.js Node.js App, which is running on port 3000.

View Nginx Configuration Code here: https://gist.github.com/learncodeacademy/ebba574fc3f438c851ae

We're also going to set it up Nginx load balancing, so the http requests will get evenly distributed between all of our servers.
See full documentation on Load Balancing (upstream) here: http://nginx.org/en/docs/http/ngx_http_upstream_module.html

Lastly, we're going to setup static file caching on Nginx, so our css, js and image files are only served from our Node.js application the first time...this DRASTICALLY improves application performance.

<!-- @section -->

# How to deploy node.js applications #1 - spin up a server

<iframe width="560" height="315" src="https://www.youtube.com/embed/W3rnQbsMb4Q" frameborder="0" allowfullscreen></iframe>

This 3-part series covers deployment of nodejs applications.
- You'll spin up and provision a server on digital ocean
- Setup automated deployment
- Then refine the deployment of your app to run as an upstart service

Prerequisite video!
- SSH Tutorial: https://www.youtube.com/watch?v=DbPDraCYju8

What we're doing in these videos is called automated-deployment. It's a part of devOps. DevOps is a set of tools/practices that focus on having a streamlined, heavily automated and reliable strategy development, deployment & monitoring of web applications.

We're going to setup a way to deploy our node app with a single command.

<!-- @section -->

# Deploying node.js applications #2 - provision server & setup flightplan

<iframe width="560" height="315" src="https://www.youtube.com/embed/XxRuW1pfGTI" frameborder="0" allowfullscreen></iframe>

In this video, we'll setup an automated deployment strategy for our node.js application.

Here's the code I'm using in this video:
https://gist.github.com/learncodeacademy/35045e64d2bbe6eb14f9

<!-- @section -->

# Deploying Node.js Applications - Deploy Node the right way - as an Upstart Service

<iframe width="560" height="315" src="https://www.youtube.com/embed/BJZZnhGtR4A" frameborder="0" allowfullscreen></iframe>

Deploy Node.js Applications the right way - as an upstart service. When you deploy a Nodejs app an upstart system service, it will always be running, EVEN if a server has to reboot for some reason.

This is the best way I've found to deploy Node.js Apps currently.

<!-- @section -->

# How to send server email with Node.js - sendgrid, mandrill, mailgun, etc.

<iframe width="560" height="315" src="https://www.youtube.com/embed/zrXOjWICmGw" frameborder="0" allowfullscreen></iframe>

If you've never sent email with a server, it's super simple! We're going to quickly walk you through how to send server email with node.js using Sendgrid - the world's largest Email IaaS provider.

Sending email from a server might feel daunting at first, but it's really one of the easier things that you can do as a web developer.

In this example, we'll wire Sendgrid into our Node.js application and send an email. The overall process will take less than 5 minutes, but Sendgrid will take up to a day to provision your account for usage in the application you're developing.

I've also tried Mandrill for email, but have to say that the results simply weren't as good as using Sendgrid in web development.
