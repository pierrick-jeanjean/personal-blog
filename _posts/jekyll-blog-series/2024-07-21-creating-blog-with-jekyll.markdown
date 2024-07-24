---
layout: post
title:  "Creating a blog with Jekyll"
date:   2024-07-21 09:00:00 +0100
categories: blog jekyll
---

Today, I decided to start my own blog. I’ve always wanted a space to share things I discovered and learned during the day at work or outside during my free time.
In order to make it quick, I looked for static site generators and based on the popularity, I selected [Jekyll](https://jekyllrb.com/){:target="_blank"}

### Pre-requisites

I began by installing [Ruby](https://rubyinstaller.org/){:target="_blank"} and Jekyll by running this command:
```shell
gem install jekyll bundler
```
*N.B: bundler is a gem manager, required here for Jekyll run*

### Generating the static site
Once installed, I just had to run
```shell
jekyll new .
```
in the folder I want and that's it the site is generated!

Then, in order to see the result, I just had to run:
```shell
bundle exec jekyll serve
```
And voilà! My blog came alive at http://localhost:4000

### Making it accessible for everyone

Since I am already experienced with Azure, I decided to host my blog on it. For that, I only had to create a *free* static webapp and directly refer the sources to my GitHub project.

In the background, Azure/GitHub set up a GitHub action to deploy my blog, magic ✨

Next step will obviously be about customizing it, but it will be for another day

Cheers!