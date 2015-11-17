---
layout: post
title:  "Exam assignment 1"
date:   2015-11-15 13:36:21
categories: jekyll update
---
<h3>What I think of pre-compiling CSS.</h3>
I think that pre-compiling CSS made things a bit more complicated at first, but once I got around the learning
curve I started to like it. <br>
What I like most about it is that you can make the code easier to read, with the nesting and 
the "cleaner" look it gives. I no longer have to keep track of several values like colours or different margins thanks to the 
variables, which is a personal favourite among the features and the technique I used the most. <br>
I've always thought CSS was fun and easy to get into but with pre-compiling CSS it gets a little bit trickier but the 
advantages it brings is worth the trouble of learning it. It makes the code smaller and much more neat-looking, as well 
as easier to keep track of when you're writing it. Using variables makes it so you don't have to write the code multiple 
times. The use of multiple files makes it easier to structure the code. On the other hand it could make it more difficult 
to debug, locate which line(s) is wrong because of the many different files.

<h3>What I think of static site generators.</h3>
When you make a website using static site generators you are very limited to one type of website, a static site, 
which is in the title. Compared to a dynamic site, static site generators are really fast to load which is why I think 
SSG is pretty handy when making websites that only displays information and not ones that need to be dynamic for the user, 
in these cases it's better to look elsewhere. <br>

<h3>What is robots.txt and how have I configured it for my site?</h3>
Robots.txt is a text file that is placed in the root directory of your website. It's purpose is to prevent or allow search 
engines and so called robots to look through the site. Before the robot visits the site it checks the robot.txt file and acts 
accordingly. "Bad" robots made by people with ill intent will most likely ignore the robot.txt file. <br>
I have, for now, set my robot.txt to not allow any robots at all. <br>
User-agent: * <br>
Disallow / <br>

<h3>What is humans.txt and how have I configured it for my site?</h3>
Humans.txt is also a text site but it is aimed for humans instead of robots. It could contain information such as 
dev team, contact info and different tools they used to make the website.<br>
My humans.txt contains name, location, some contact information, date the site was created and some of the tools I used.

<h3>How did I implement comments to blog posts?</h3>
Because static sites doesn't offer anything in terms of user interface I had to look at other tools to use. I chose to use 
Disqus, which is a commonly used, free comment system. The implementation process was smooth and pretty easy, all that needed 
to be done was register for Disqus then add the snipped of code to the blog post code.

<h3>What is open graph and how do you make use of it?</h3>
Open graph affects the way a site is presented when shared on social media like, twitter, facebook or slack. Instead of just 
a boring line of text, your link could have a wide range of looks. You use open graph by placing its meta tags in your sites' 
head-tag, just like you normally would. The ones I have in mine is title, type, url and img but these are just the tip of the 
iceberg, a full list can be found on open graph's <a href="http://ogp.me/">website</a>.


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help