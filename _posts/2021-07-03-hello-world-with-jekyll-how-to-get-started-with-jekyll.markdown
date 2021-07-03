---
layout: post
title:  "Hello World With Jekyll! (How to Get Started with jekyll)"
date:   2021-07-03 13:36:00 +0200
categories: [Jekyll, Framework, Development, Ruby]
---
I was hungry to get into something new when Jekyll came up in my Twitter timeline. The idea of blogging using markdowns and static site generation sounded much more attractive than solutions requiring complicated setups, databases and expensive maintenance. I am documenting here the path I followed to get my first Jekyll blog.

Hi everyone, my name is Wellington and I am a computer scientist and developer based in Malaga, Spain. My expertise goes around programming, infrastructure, physics and maths. I love to get myself involved with new projects and I am constantly learning new things.

![Jekyll](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/001-jekyll-logo.png)

I have been courting Jekyll for few weeks now and recently I decided to dedicate some time to get familiar with the framework. Jekyll is a static site generator wrote in Ruby and with full support for markdown language, turning the blogging experience much faster and easier.

Jekyll have unbeatable features that makes it much faster and secure than all other blogging frameworks out in the market. 

* Site generation
* HTML and CSS only
* No Database required
* Updated via Markdowns

Jekyll is a static site generator, that means no need of interpreters, complicated servers or database to have your blog live, that represents a massive cut of costs in infrastructure, maintenance and security.

My starting point with Jekyll was to simply get a blog running, but after hours of research I realised that the framework is very useful for corporative websites looking to reduce costs from maintenance and infrastructure.

I will also mention about how easy it is to get started with Jekyll. It can be a little different in the beginning, mostly if you are already familiar with programming languages, the truth is that you won't need any programming skills to get a site up and running.

Jekyll is an awesome framework for front-end developers with experience in HTML, CSS and JavaScript.

![Jekyll](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/002-ruby-logo.png)

Jekyll is written in Ruby, an interpreted programming language used for science, AI, software and web development, where Ruby is very popular with the Framework Ruby on Rails.

To kick started with Jekyll the very first step is to download and install Ruby in your computer. You can find the latest version for your operational system on the official Ruby's website. 

Click here to download the latest version of Ruby for your operational system.

With Ruby installed in your computer, it is time to work in some commands. Open your terminal, shell or command prompt and jump into Desktop folder. CD Desktop

![Terminal](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/003-cmd.png)

1. Use the following command to install Jekyll and Bundle: `gem install bundle jekyll`

Wait for the download and installation to complete.

2. Use the following command to create a Jekyll project: `jekyll new my-blog`

This will create a new folder named my-blog in your desktop. Now jump into the folder with the command `CD my-blog`.

3. Use the following command to see files created by Jekyll: `dir` or `ls` (Mac or Linux)

This will list all the files that Jekyll created in the folder.

![Terminal](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/004-cmd.png)

4. Use the following command to build and serve Jekyll: `bundle exec jekyll serve --watch`

Now Jekyll has built up your blog and is serving at the host http://localhost:4000/. You can access this address with your browser to see your Jekyll blog built in your computer.

![Terminal](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/005-cmd.png)

Jekyll is a static site generation that works with templates and markdowns, and to understand how to make changes and updates in our blog, we need to have a close look at the file system inside the folder `my-blog`.

To perform any changes or make updates in your blog, I strongly advice an IDE of your preference. I am using Sublime Text, but you can pick the one you like most.

Open the folder `my-blog` in your IDE and that is what we see.

![Terminal](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/006-localhost-chrome.png)

Folder `_posts`: Contain markdown files of your posts, posts must be named following this rule: `YEAR-MONTH-DAY-title.MARKUP`

Example:  `2021-07-03-welcome-to-jekyll.markdown
`
Folder `_site`: Contain the build up of your site. You don't need to change anything in this folder.

File `.gitignore`: GitHub .gitignore file.
File `404.html`: 404 Erro Page.
File `_config.yml`: Configuration file of your blog.
File `about.markdown`: About page file.
File `Gemfile`: Ruby configuration file.
File `Gemfile.lock`: Ruby lock file.
File `index.markdown`: Home page of your blog.

The first folder to look at is `_posts`. The only fine in it is named something like `2021-07-03-welcome-to-jekyll.markdown`. That is a markdown file and what Jekyll uses to generate the content and site structure of your blog.

All posts must be created in a markdown file named accordingly to the standard.

Example: `2021-07-03-welcome-to-jekyll.markdown`

![Sublime Text](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/007-sublime-text.png)

When you open the only file in the folder `_posts`, you will see that the file have a head that looks like this.

```Jekyll
---
layout: post
title:  "Welcome to Jekyll!"
date:   2021-07-03 00:00:00 +0200
categories: jekyll update
---
```

All posts must have this head to define the layout, title, date, time and category of the update.

Jekyll will use the file name to build your site-map structure, but the information displayed from every posts, comes from the head of the file.

If you want to create a post with the title “Hello World!”, here are the steps to take.

1. Create a file named 2021-07-03-hello-world.markdown in the folder `_posts`
2. Add the following head to the markdown file.

```Jekyll
---
layout: post
title:  "Hello World!"
date:   2021-07-03 00:30:00 +0200
categories: jekyll update
---
```

![Sublime Text](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/008-sublime-text.png)

After the mandatory head, you can work in your post freely using markdown to build your content. If you are not familiar with markdown, check the Jekyll docs to get started.

To understand more of Jekyll file system, we will now have a look at the file `about.markdown` in the root of the folder `my-blog`.

![Sublime Text](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/010-sublime-text.png)

When you open the `about.markdown`, you will realise that this file also have a mandatory head. It looks like this:

```Jekyll
---
layout: page
title: About
permalink: /about/
---
```

It is slightly different than the post head, but also super important for the site organization and display of the content.

If you want to create a page to receive contacts, these are the steps.

1. Create the file `contact-me.markdown` in the root of your project folder.
2. Add the following head to the markdown file.

```Jekyll
---
layout: page
title: Contact Me
permalink: /contactme/
---
```

Right after the head, you can also edit freely the content of your page using markdown.

![Sublime Text](https://wellyington.github.io/blog/assets/hello-world-with-jekyll-how-to-get-started-with-jekyll/011-sublime-text.png)

If we update our site now on the local server, you will notice that your updates are built in your blog.

The post **“Hello World!”** and the page **“Contact Me”.**

Congratulations, now you are officially introduced to Jekyll. There are more to learn about the framework, but now you have a better idea how to start a project and how to take your first steps by your own.

Jekyll's official documentation provides a large amount of handful content to help on your your walk-through.

In a future append to this article I will cover Jekyll includes, templates and how to customize Jekyll´s Minima built in theme with your own CSS.

Jekyll is easy, fast and secure to work and the learning curve is really fast. Anyone with little technical skills is able to get a Jekyll site running in a couple of hours.

The framework is useful for blogs, corporative websites and with a little of creativity you can connect it to other services using JavaScript and APIs. 

It is worth to know how Jekyll works in your personal projects and how to apply for your clients.

If you are a front-end developer, you have just gained freedom from back-end developers and can now work in your own generated sites using the simplicity of Jekyll.

The average pay for a professional working with Jekyll is $20 USD to $120 USD per hour on Upwork.

Thank you for reading. Please share this article in the communities that you belong and let everybody knows how simple and fun it is to blog using Jekyll.

Reach me out on Twitter, Instagram or Facebook and let's start a conversation about Jekyll, I am prompt to help you with your doubts and I am interested to know what are your ideas with Jekyll.

Have fun with your new stack.