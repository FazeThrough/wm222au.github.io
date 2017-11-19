---
layout: post
title:  "Examination 1"
date:   2017-11-04 17:53:55 +0100
categories: blog
---

### What do you think of pre-compiling your CSS?
It greatly increases productivity whilst using almost the exact same syntax. 
#### Compare to regular CSS.
Nesting, loops, inheritance and extensions allow web developers to create and design things much quicker. For example, such things as media-queries can be globally set via a variable which allows devs to greatly increase the speed in which they can create dynamic and relative websites. I'd say the only real disadvantage is the diffrent codebase and the more strict manner of CSS (which in some cases allows for greater readability).

#### Which techniques did you use?
Jekyll, Sass, HTML5, CSS.

#### Pros and cons?
1. Pros
    * Avoid repeating yourself (DRY).
    * Reusable functions (mix-ins), somewhat more similiar to a programming language.
    * Ability to structure styling via imports and defining variables.
2. Cons
    * Codebase doesn't have the same appearance after compilation, can be hard to debug.
    * Requires a pre-compiler to create readable files for the browser.


### What do you think of static site generators?
I like them. It removes DRY from static websites and allows for quick and dynamic delivery of information. It also requires less overhead than other solutions such as wordpress and the like, since everything that is generated is HTML / CSS / JS.
#### What type of projects are they suitable for?
Presentations of business, services, mobile and web apps. The final content that gets generated is generally very small, which allows the website / server to handle a lot more requests. You can limit the amount of traffic needed to present your product and instead place the product / service on a diffrent server. Since the compiled website only consists of HTML and CSS theres nothing to hack, providing security for websites designed only to mediate information.


### What is robots.txt and how have you configured it for your site?
Robots.txt informs crawlers (specifically or not) about what pages they should index and which they should not. I've configured mine to allow all crawlers complete access, since this website has nothing to hide and benefits from being publicly available. Important to note that crawlers can ignore robots.txt


### What is humans.txt and how have you configured it for your site?
Humans.txt offers is a textfile useful for presenting the contributors to a website. I've configured mine to represent my name, social media accounts, location and the tools and standards I used to create the website.



### How did you implements comments to blog posts
Using disqus and their javascript. Implemented in post.html via includes. Every post made with layout "post" will have a comment-field.


### What is Open Graph and how do you make use of it?
Open graph allows other services to display relevant information about the website and the specific page. These services then retrieve the information Open Graph points them to, such as a description and image and presents them to the user.