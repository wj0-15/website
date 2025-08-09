---
title: 'Static Sites'
date: '2024-05-18T07:52:38+02:00'
# weight: 1
# aliases: ["/first"]
tags: [""]
author: "Joh"
showToc: true
TocOpen: true
draft: false
hidemeta: false
comments: false
description: "... are a better way to create smaller blogs and websites and I wanna show you how!"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/wj0-15/website/tree/main/content/posts"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
## At first, what exactly is a static site?
There are a lot of explanations out there, but my extremely simplified version is: It's a website which doesn't need much resources and is built similar like the websites in 90s. Small files, Easy to serve and display, no application running constantly (besides the webserver it self) and no database. But in modern days, this is impractical due to fast and frequent changes to a website, and only a few people know and want operate those changes directly in HTML or CSS Code. Thats where a static site generator like Hugo comes in.
## So what does the Static Site Generator do?
In easy words, you can give him the content of your website, and it will build every time the Static HTML Files for you. That means, no fiddling with html code directly, while having all the benefits of it in a simple way.

In my example on this website, I looked up a template how it should look like, and now only feed normal text files to it, to generate this post.
The other parts will be taken by the Static Site Generator
## What are the benefits?
The easy one here is less security risks then typical CMS Solutions when maintaining the site. I mean, I generate the site which does not (or less) contain any interactions which need to be handled by Databases which could be vulnerable or other Frameworks which allow interaction with the server, like PHP for one prominent example.

But most importantly, my website doesn't get more vulnerable over time.
In case of classic CMS Solutions, you need to maintain and regularly update those just to keep the site alive even if you do not add content to it.
That also means, if I abandon this site (or just not post to it for 1 year), it doesn't get more vulnerable, and some Information just don't change that often.
Its always easily maintainable and changeable, but doesn't require constant work on it.
## Why not everybody uses it then?
This is a good question. There are also some downsides that need to be considered when doing this.

Compared to a ready-to-go CMS Solution, you need to gain knowledge on setting it up and also where to serve it. Nowadays you can build up a website with zero knowledge about them. Don't get me wrong, its awesome on how easy you can make websites without knowing what you actually do.
In terms of ease of use they are also much easier to maintain for the target-group.

Also the text-files I mentioned earlier need to be in a specific format and only allow formatting like **bold**, *italic*, and ~~strikethrough~~ via syntax which you need to learn first. I don't say it's unmanageable and even would say it's no hurdle to learn it, but compared to the existing solutions it doesn't stand a chance for most users. And motivation to learn this "just to have a website which generates users or gaining customers" is not there and thats understandable.
## To summarize
Is a static site generator for you?

I would say it depends! (Which I know many people will stop here because it's more complicated then a simple Yes/No)

If you have a set of basic information which doesn't or not very often change (Like Contact Details, Addresses for Business, maybe even Menus) I would argue that thinking again of switching to a Static Site can be a benefit. If you're not sure on how, [contact me]({{< ref "/about/" >}}) for consulting or just ask "the IT Guy" to help you out in this one.
If setup right this website would be a OneTime Cost and doesn't need maintaining as much as your classic site.

But if you have (or want to have) a website where you regularly post pictures or video content which is not embedded through external sites, then I would choose a different solution. I don't wanna say it's impossible here as well, but the effort that you need to put in compared to a ready-to-go solution is not worth it.

Okay thats where I leave it for today.
If you have questions, feel free to [reach out]({{< ref "/about/" >}}).

Thanks for your time! And have a great day!

~Joh