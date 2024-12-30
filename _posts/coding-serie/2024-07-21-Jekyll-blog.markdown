---
layout: post
title:  👨‍💻 Jekyll blog
date:   2024-07-21 09:00:00 +0100
categories: coding
---

Today, I’ve made the decision to start my own blog. I’ve always wanted a platform to share my discoveries and learnings from both work and my free time. To expedite the process, I researched static site generators and ultimately chose Jekyll due to its popularity.

### Pre-requisites

I began by installing [Ruby](https://rubyinstaller.org/){:target="_blank"} and [Jekyll](https://jekyllrb.com){:target="_blank"} by running this command:
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
And voilà! My blog came alive at [http://localhost:4000](http://localhost:4000){:target="_blank"}

### Making it accessible for everyone

Given my existing experience with Azure, I opted to host my blog there. 

The process was straightforward: I created a free static web app and linked it directly to my GitHub project. 

Behind the scenes, Azure and GitHub collaborated to set up a magical GitHub action for deploying my blog. 

The next step, of course, will involve customization, but that’s a task for another day

Cheers!