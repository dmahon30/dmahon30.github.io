---
title: "How I created this website"
date: 2021-11-01T08:42:40-04:00
---


# What I was trying to do

+ I'm trying to expand my skillset when it comes to web design - I've worked with dynamic websites before like Wordpress and Wix, but I've never made my own static website. Suffice it to say, I am excited to learn more about how to tweek these sites to suit my design needs.
+ I knew I need to generate a URL via Github, then upload the Hugo template to that rep in order for Github to read it as a website.
+ [Static website tutorial](https://graddh.netlify.app/docs/tutorials/static-websites/)

___
## How it connects to my research

+ I plan on using static sites to host a digital portfolio, as well as hosting the final DH creation project that I'm working on.
___
## What I did

+ step 1: Build site with GH pages.
	+ Created new repository in Github called `dmahon30-github-io` 
	+ This format is what allows Github to read the repo as a website.
+ step 2: Content
	+ Add an .md file to the repo and Github will add it to the web content.
+ step 3: Enable Pages (Settings of your repo)
	+ Ensure the repo is in the `main branch` and you've got a basic website!
+ step 4: Adding template from Hugo
	+ Download template.
	+ Upload according to the [Quick Start tutorial](https://gohugo.io/getting-started/quick-start/).
	+ Change the content in the Example.site in lieu of step 4 in the above Quick Start tutorial (easiest way to manipulate the template) and upload that template content to your Github website repo.
	+ Note: Need to add the content from the PUBLIC folder generated.

## Challenges 

Biggest challenges for the static website

*Adding the Template*
+ I needed to move template directory to my ’themes’ folder in my site directory in order for the template to be read.

*Pushing local rep (public) to remote repo on Github*
+ I had to use the command git pull I think and then these commands that were pulled from the command line:

```
`	git commit -m "first commit"
		git branch -M main
		git remote add origin [repo URL]
		git push -u origin main`
```

*Resources that I used to Troubleshoot*:
+ [https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7](https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7)
 
+ [https://stackoverflow.com/questions/24114676/git-error-failed-to-push-some-refs-to-remote](https://stackoverflow.com/questions/24114676/git-error-failed-to-push-some-refs-to-remote)

+ [https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/#sample-pagemd](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/#sample-pagemd)

+ [https://gohugo.io/getting-started/quick-start/](https://gohugo.io/getting-started/quick-start/)

*perhaps the most important resource is this one*:

+ [Creating a Blog with Hugo in 10 Minutes](https://www.youtube.com/watch?v=LIFvgrRxdt4&ab_channel=RyanSchachte)

## Thoughts on where to go next

I'd like to populate the site with images and sound files, so I'm working on that now - wish me luck!

![](/images/cat-computer.jpg)