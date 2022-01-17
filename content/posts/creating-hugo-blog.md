---
title: "Starting a blog with Hugo... lots to learn!"
date: 2022-01-16T21:25:15-05:00
readTime: 3
tags: ["podcast", "blog", "hugo"]
draft: false
---

The other day, I watched a YouTube presentation called ["Give Yourself a Blog for Christmas"](https://www.youtube.com/watch?v=NKHF5VZmCig&t=831s) 
that one of my favorite podcasters, Jack Rhysider, shared. Jack argued that anyone can benefit from a podcast, whether
it's for posting documentation to look back on later or to share out ideas for others to benefit from on the vast internet. <!--more-->

This really inspired me - why not start a blog? I think it'll be a fun exercise to deliberately document my findings, 
share out anything I've learned, or just write about anything that's been on my mind.

So... what next?

## Choosing my blogging tool

Knowing that I'm particular and I will want granular control over the look and feel of the blog, I knew I would have to find a some sort of site generator with an extent of customizability. Plus, this could make for a cool project to learn about a new tool.

After some searching around, some names I found coming up frequently were:

* Jekyll
* Wordpress
* Gatsby
* 11ty
* Hugo

They all had their pros and cons, but I saw a couple of intriguing examples leveraging Hugo that made me feel confident that it was flexible enough to meet my needs. Hugo it is. 

## Setting up Hugo

I followed the [Binary (Cross-platform)](https://gohugo.io/getting-started/installing/#binary-cross-platform) instructions in the Hugo documentation to install it on my Windows computer. This required me to:

1. Install [Go](https://go.dev/dl/), because Hugo is powered by Go
2. Download the [Hugo binary](https://github.com/gohugoio/hugo/releases)
3. Add the `hugo.exe` file to my Windows PATH so that the command line will recognize the `hugo` command
4. To test that everything is working, run the command `hugo version` in Command Prompt to see a version number

With everything installed, creating a project was fairly easy. In your desired directory to store the project (I'd recommend a Git repository for version control) run the command `hugo new site sitename`. That's it - Hugo will generate the files and directory structure that you need.

But... there's nothing to see yet. You'll need to add a theme to make it look pretty!

## To be continued...

_Side note: I would highly recommend checking out Jack Rhysider's podcast ["Darknet Diaries"](https://darknetdiaries.com/)! 
He shares stories from the "dark side of the internet" about various hackers, exploits, social engineers, and more with
excellent music/production quality._