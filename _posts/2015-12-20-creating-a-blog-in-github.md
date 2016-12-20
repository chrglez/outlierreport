---
layout: post
title: Creating a blog in Github
tags: [Jekyll, blog, Github]
---

As I told in the presentation post, when I started to use R I founded that in each project I did, I had problems developing it and I needed to search solutions to these problems. For this reason I decided to create a blog. To have a site to put all the problems I founded and the steps I followed to solve them. So, I thought that it would be appropiated tell how my first expirience creating a blog was.

My fisrt attempt was creating a blog in Wordpress. So, I started to search a package in R that allows posting in WordPress. Searching, I founded [the blog of Yihui Xie](http://yihui.name/knitr/demo/wordpress/). There, he tells that you have an alternative for blogging: Jekyll. The key was:

> ...and that is why you, as a cool hacker, should blog with Jekyll instead of WordPress.

And I wanted to be *a cool hacker*.

## Creating a blog using jekyll. 
-----

**Jekyll** is a static site generator.

As they tell in their [site](http://jekyllrb.com/):

> Jekyll is a simple, blog-aware, static site generator. It takes a template directory containing raw text files in various formats, runs it through a converter (like [Markdown](https://daringfireball.net/projects/markdown/)) and our [Liquid](https://github.com/Shopify/liquid/wiki) renderer, and spits out a complete, ready-to-publish static website suitable for serving with your favorite web server.

<img src="http://jekyllrb.com/img/octojekyll.png" alt="Jekyll's Octocat mascot" width="256">

You have two options to bulid a blog with jekyll. Install it locally or use Github as a host for your blog. In this post I will explain this second option because it was my first choice when I decided to create an attemp of blog and because I thought it would be easier (and certainly it is but only a bit that the first one).

### Steps to create a blog in Github

Create a blog using jekyll is not very complicated. It takes only 10 minutes and it is free. We can use GitHub to host our blog and as they use the engine jekyll to create their sites, why do not we use the same engine to generate our blog? 

* Of course, you have to have a Github account
* Fork one of the hundreds jekyll templates in Github. You have more to choose in [jekyllthemes.org](http://jekyllthemes.org/) and this one is a sample of the other sites you can find on internet with jekyll's templates.
* Click on the settings button and change the name of the repository. The url of your blog will be *your-nick-name/github.io/* **name-of-repository**. 
* Using the edition panel of Github edit the *_config.yml* file. Within you can change the name of the blog, the description and many other things the creator of the proyect thinks is necessary to configure the blog.
* If the *markdown* setting is different of *kramdown* you have to change it, and *highlighter* by *rougue*.
* Then click on *commit changes* button.

If everything is ok you have configured your blog.

### Publishing posts

* Go to **_post** folder
* Edit a existing file or create a new one. The file's name must start with a date in the format *yyyy-mm-dd* and the title of the post separated by a hyphen "-".
* The most importan part of the file is the heading. If you are creating a new file, you can copy and paste the heading of other post and modify the elements of the headings like **title:**.
* Then write your post following the markdown language. Here you have a [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to help you when you write in this language.
* When you are happy with your post click on the **commit changes** buttom.

### Upload our works in R
