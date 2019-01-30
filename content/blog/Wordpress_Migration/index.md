---
title: 'Why I Moved Off of Wordpress'
date: '2019-01-30'
---
So it has only been a couple of days since I completely moved my content from Wordpress onto this new site, and I already feel slgihtly more in control from the getgo. I started the Wordpress blog with the hopes of being able to not only have a custom domain, but having the ability to get custom themes and be able to track stats was also a major plus.

So what happened? Why did I decide to move away from the platform. Well, there are a few reasons:

1. I wanted to have a little more control of the codebase running my site, but not get my hands dirty with the backend necessarily (yes, I am aware I can do that by installing wordpress locally, but I can't exactly run if of my local machine locally all the time.)
2. I wanted to try a different platform where I can control the theme, have different pages out of the box, and have a relatively simple method of making posts.
3. Wordpress's hosting was stable, but I slowly realized how irritating their business model is (my biggest gripe with the CMS).

So what went wrong. Well, It all came down to the business model. When I first started on Wordpress, I payed roughly $50 for a year of service. Not too bad, truth be told. However, about 2 montsh ago, I get an email from them regarding a change of plan pricing, and that now they will charge an extra $26 for the custom domain on top of the $50 for the personal plan. That, for me, is completely excessive when you can get your own custom domain from sites like GoDaddy and HostGator for extremely dirt cheap. This, for me, is unacceptable, and thus, moving away from the platform.  

For that reason specifically, I decided to start looking for a better method of owning and running a blog. Which led to my next question: "How am I going to build it and where am I going to host it?"

I first started to look for the code base on to which to start the site, and remembered [Gatsby](https://www.gatsbyjs.org/), which is what is currently running the site now. With one starter, I was able to get a theme I liked out the door fairly easily and would be MUCH simpler to role out posts, using a simple directory structure and Markdown for formatting.

After deciding on that, my main concern was hosting. I wondered where I could do it that was free, fast, and I could get posts up from anywhere I was. Luckily, there were several options I had in mind:
* **Github Pages** - Github's own webhosting servies is simple enough and can be managed through my own Github repo, but the problem was that with the first class citizen being [Jekyll](https://jekyllrb.com/), a static site generator built using Ruby that I didn't enjoy using, I decided against it.
* **Gitlab Pages** - Also a self hosted service using Gitlab repos, but what got me away from it was the uncertainty of configuring the site itself, and I wanted something thaat I didn't have to tinker with all that much.
* **Netlify** - the choice I made in this scenario, it was recommended to me by [Zaydek](https://twitter.com/username_ZAYDEK) on [this tweet](https://twitter.com/username_ZAYDEK/status/1087141492894793734). This platform is fast, easily configured requiring only access to the repo for your site, and automatically updates every time you push a change to your repo/

As you can see, I love Gatsby + Netlify. It made it super quick and easy to get my content off of Wordpress, and upload it in basically a day. Using both Gatsby and Netfliy have just changed the way these kinds of projects work, and I'm glad to have chosen this method.