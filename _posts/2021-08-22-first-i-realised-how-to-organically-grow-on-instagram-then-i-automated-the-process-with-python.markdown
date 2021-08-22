---
layout: post
title:  "First I realised how to organically grow on Instagram, then I automated the process with Python."
date:   2021-08-22 22:39:00 +0200
categories: [Instagram, Social Network, Development, Python]
featured-image: https://miro.medium.com/max/700/1*ktB_9rKyU6_Eeb5Zom6QLg.jpeg
---
I never thought that two of my passions would collide together, coding has been my thing since I was 11 years old, that time I tried to do all things with a computer, and internet marketing represents my professional development in recent years.

<hr>

The path for this article started years ago when I developed imminent interest on Instagram and decided that I needed to realise what was the best practice to grow an account organically. My motivation was commercial, as I had just started to work in e-commerce projects and wanted to turn Instagram into one sales channel for my products.

My first wrong belief was to think that Instagram is easy, I didn’t start to make real advances and open my mind to the platform before a whole year trying and failing. For 1 years I struggled in all kinds of erroneous ways to use Instagram.

It was only after a couple of key pieces of information that my results started to change. I was in a hostel in Budapest back in 2018 when I bumped into a blog post that explains how to build engagement using the explorer from Instagram, yes, the little magnifier search icon in the app.

{:refdef: style="float: left;"}
![Instagram](https://miro.medium.com/max/432/1*Igz14L-LtIhqe9vvWEBIJg.png)
{: refdef}

While most people think that successful Instagram accounts are built only with amazing content or paid followers, the real tool to grow any Instagram account is right under our noses.

The posts displayed on the explore section are relevant to your account, based on Instagram algorithm, it refers to your previous recent interactions, and the more you interact with this content, the higher are the chances that you will get interactions back.

I realised that for every 100 liked posts in my explore section, I would get 1 to 3 new followers and 6 to 10 new post interactions. That is not a lot, but it is something to work with if you are considering the numbers.

Remember that every time you like a post, send a comment or follow an account on Instagram, the person will receive a notification and most probably check your profile back. Basically if you give 100 likes, that equals 100 people receiving notifications from your profile. In the starting point, this will automatically increase traffic for your profile from 100 users.

Instagram has some limits that might frustrate your plans to go on the app and simply start to give like non-stop for the whole of the day. They won’t allow you to give more than 1000 likes per day, and the safe-zone to don’t get your account locked out is around 700 likes per day.

Now we know our limitations on Instagram, so if we succeed to interact with 700 posts from my explorer in a day, we might get 7 to 14 new followers and hundreds of interactions every day.

This was my initial logic, and it works flawlessly, the only real problem was that I hardly succeeded in interacting with 700 posts in a day, and in most productive days I wouldn’t accomplish more than 200 interactions in a day.

Even with such inferior performance, results were still happening as expected. After applying in my personal account and 2 other business accounts I have managed to increase traffic and engagement considerably.

To work exclusively with the explorer section was my best practice to build an audience on Instagram until I met Hannah in Malaga, Spain in the middle of summer 2019, a community manager from Newcastle Upon Tyne who had just moved to Spain.

When I shared with her what I was doing on my Instagram accounts, we realised that she was actually doing the same thing, but with a slightly different detail; while I was building engagement only from the explorer section, Hannah was going for relevant hashtags.

The concept is simple, instead of interacting with posts from the explorer section, she was interacting with posts from hashtags related to the content in question, this way she guarantees a much better target audience.

I started to apply her technique in my accounts, and while in my personal account the results weren’t much different, in one shop account that I manage we had 955% increase in engagement and 2310% increase in sales.

![Money](https://miro.medium.com/max/2400/1*VQNxso5IKAD_tLZUR58F-Q.jpeg)

As a community manager I appreciate all kinds of engagements, but when the sales gain a considerable increase is that I start to take things more seriously.

I joined forces with Hannah and we started to work together in a couple of projects of mine, the results started to get better day after day, but we still had one little problem, none of us were still engaging with more than 200 posts per day.

That has been our struggle when it comes to building engagement in the Instagram accounts we manage, and that also means that the more clients we would help, the lower would be our performance.

I am just setting up my agency to work with external clients. We are doing well when it comes to our own projects, but if the demand for work increases because of external clients, I am left with only two options on my hands; to hire new people to work with us or to automate the repetitive work so it would free time in our schedule.

I am happy to hire new people, but that would not fix the initial problem, as I have already experienced that a person won’t interact with more than 200 posts per day, so to make the most of my limits on Instagram I needed some kind of super-human power.

My best option was automation.

![Robot](https://miro.medium.com/max/700/1*pxdLHNvFT6OMb_ayqhxkGg.jpeg)

The very first thing I needed to do was to recycle my development skills and get familiar with coding in Python. Hands up for the guys at [Free Code Camp](https://www.freecodecamp.org/), after 4 hours training I was familiar with the language and ready to move ahead.

Python alone isn’t enough to build the type of browser automation that I had in mind, so I had to get familiar with the library selenium and Chrome webdriver to make it work. Not a big deal as well and I have managed to find plenty of documentation about everything I needed on Google.

Now that I know how to code Python and use Selenium, it is time to put the project together and create an engagement robot for Instagram.

My advantage is that Python has a very fast learning curve, and even when the project sounded complicated in the beginning, it was easy, fast and fun to put things together.

![Robot](https://miro.medium.com/max/2400/1*82pedrUzDU90Ci7WqPbsKA.png)

Here are the robot functions:

1. Collect a hashtag for engagement.
2. Collect a limit of engagements.
3. Collect a username.
4. Collect a password.
5. Connect to Instagram.
6. Close Notification.
7. Open profile page.
8. Search for hashtag informed.
9. Open the first picture from the search result.
10. Interact with the amount of posts informed.
11. Open profile page.
12. Close browser.

And here is a screenshot of the robot’s command line:

![CMD](https://miro.medium.com/max/2400/1*_cLPy453z7dO8HhWKXASkw.png)

It took me only a couple of hours to write 45 lines of code and give life to my Instagram bot and a few more hours to find the right parameters and timing between one engagement and another, so Instagram wouldn’t spot the interactions as coming from a robot.

It is certainly the most effective tool that I have to use as a community manager at the moment.

The robot executes the function exactly as described, it will first collect information about your engagement, then it will connect to Instagram, open the indicated hashtag, interact with posts and close when completed.

The script will take the average time of 5 minutes to complete 50 likes. I strongly advise to run the bot several times with smaller amounts of engagements, don’t run all the 700 engagements in a single shot in order to keep the health of the Instagram account.

Now, executing the robot between 10 to 14 times a day, setting the engagement to 50 posts every time, I guarantee 500 to 700 engagements per day and all the process is automated.

I have made available the source code to my robot on Github, so if you are familiar with Python you can try the bot yourself.

Get the source code [HERE](https://github.com/wellyington/maia-instagram-bot)

For the time being the bot is only engaging with posts from informed hashtags as the urgency of the project was to generate engagement from target audiences and increase sales on online stores, but the next function to be added in my robot is the skill to engage with posts from the explorer page.

If you have no clues about Python, but you are a community manager and you would like to adopt my robot as your tool, please send me a message on [Instagram](https://instagram.com/wellyington/) and I will be happy to help you out.

Check out the video of the robot in action:

<iframe width="560" height="315" src="https://www.youtube.com/embed/vvYO4hLLv8A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Do you like the bot and the publication? Please support it here on medium and spread the word among your crew, I am sure this little piece of script will be super useful for many people in the community management business.

Remember to follow me on Instagram, join the conversation, share your ideas and get updates about what I am involved with.

[Follow me on Instagram.](https://instagram.com/wellyington)

[Follow me on Twitter.](https://twitter.com/wellyington)

I hope this article adds value for your professional development and that I have helped you with a little light for your journey in direction of your goals.

Thank you for passing by. Until next time.

![Data Driven Invest](https://ucarecdn.com/4c04fcf1-36e6-49a9-b2fb-9a82886af1a1/DataDrivenInvestor2.png)

This publication came first on [Data Driven Investor](https://medium.datadriveninvestor.com/first-i-realised-how-to-organically-grow-on-instagram-then-i-automated-the-process-with-python-2a46ccd33abe) on May, 3rd, 2020.