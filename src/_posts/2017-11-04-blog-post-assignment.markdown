---
layout: post
title:  "Examination 1"
date:   2017-11-04 17:53:55 +0100
categories: blog
---

### What do you think of pre-compiling your CSS?
#### Compare to regular CSS.
It greatly increases productivity compared to regular css. For example, such things as media-queries can be globally set via a variable which allows devs to greatly increase the speed in which they can create dynamic and relative websites.

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
I like them. It removes DRY from static websites and allows for quick delivery of information. 
#### What type of projects are they suitable for?
Presentations of business, services, mobile and web apps. You can limit the amount of traffic needed to present your product and instead place the product / service on a diffrent server. Since the compiled website only consists of HTML and CSS theres nothing to hack, providing security for websites designed only to mediate information.


### What is robots.txt and how have you configured it for your site?
Robots.txt informs crawlers what pages they should index and which they should not. I've configured mine to allow all crawlers complete access, since this website has nothing to hide and benefits from being publicly available.


### What is humans.txt and how have you configured it for your site?
Humans.txt offers is a textfile for presenting the contributors of a website. I've configured mine to represent my name, social media accounts, position and the tools and standards i used to create it.



### How did you implements comments to blog posts
Using disqus and their javascript code in a seperate file. Implemented in post.html via includes.


### What is Open Graph and how do you make use of it?
Open graph allows other services to display relevant information from a link to the users it was posted to. 