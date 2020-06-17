---
title: Quickly build a similar site 👶
date: 2020-01-03
modified: 2019-08-29 09:24:47 +07:00
tags: [blog, netlify, jekyll, github]
description: All the services are free, a source code this site placed on github repository and intergration with netlify service, another service that you can use is github page for hosting your own static site.
---

This website was made using Jekyll, an open source static site generator, and a simple theme called [klisé](https://github.com/piharpi/klise).

<hr>

The source code can be found at this [github](https://github.com/piharpi/mahendrata.now.sh) repository. Here is a link to [netlify](https://netlify.com) if you would like to host your own static site for free.

<hr>

#### Create a site

In order to create your own site you will need the tools below.

#### Requirements

- [Ruby](https://www.ruby-lang.org/en/downloads/) programming language
- [Git](https://git-scm.com) (version control)
- [Netlify](https://netlify.com) and [Github](https://github.com) account
- [Bundler](https://bundler.io)

#### Installation

First, you will need a [SSG](https://www.staticgen.com/). I'm using Jekyll because I'm already familiar with it. Open your terminal and type the commands below:

```bash
$ bundle install jekyll # installing jekyll in your machine
$ jekyll new my-site && cd my-site # create new jekyll project
$ jekyll s # run jekyll server
```

Now that jekyll is running on your local machine, open your browser and go to `localhost:4000`, the default address from jekyll. Press <kbd>CTRL</kbd> + <kbd>C</kbd> to stop the jekyll server.

#### Adding remote repository

Before we adding remote repository, you must have [github](https://github.com/new) repository, if already have repository, just add github remote address to your local folder, with the following commands

```bash
$ git init # initializing project folder
$ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git # change UPPERCASE with your own!
$ git add -A && git commit -m "Initialize" && git push -u origin master # push code to github
```

Now check your github repository, make sure the files is uploaded correctly.

#### Deploying to netlify

Go [netlify](https://netlify.com) dashboard, and following this step.

1. click `new site from git`, then choose `Github`.
2. then choose your repository where is the jekyll sources uploaded.
3. netlify smart enough to configuring, we just need's are hosting's are hosting's are hosting's are hosting to click `Deploy site button`.

Wait for moment, and voila..! your site's are hosting and using `.netlify.com` tld, if your website wants to look professional, just buy a domain from your favorite domain store. or if you the first time, I advice using namecheap.com*(isn't sponsor)* \*based on my experienced it provides good service and have various TLDs.

So, what you waiting for, just create your own website for free.
