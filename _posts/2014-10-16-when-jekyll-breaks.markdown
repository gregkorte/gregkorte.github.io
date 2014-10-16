---
layout: post
title:  "Jekyll file structures"
date:   2014-10-16 14:21:33
categories: NSS Week One
---

When I first started to work with Jekyll I found the file structure a bit confusing. As of this writing I have managed to work my way around the file structure enough to possibly shed some light on the way some of these structures interact with one another.

The first issue I encountered was with getting my newly created pages to show themselves on my test server. Tackling this issue first seemed the most important since a site with no pages isn't much of a site. Here is the file structure for my localhost.

![Jekyll Root](/images/posts/jekyll_root_files.png)

The folders that are highlighted are folders I created so that when someone browses to my portfolio for instance, the URL will look like this http://gregkorte.github.io/portfolio/ and make sense.

After creating the folders I populated them with two files. In the instance of my portfolio, I named one portfolio.md and the other index.html. The portfolio.md file is to hold my markdown, and the index.html file is to act as a root for that particular folder so that clicking on the portfolio link pulls the index file.

![Portfolio Root](/images/posts/portfolio_root_file.png)

After making these corrections to the directory structure I was finally able to view all of my pages, and the URLs looked the way they should.

Next up I will review how I was able to create my own navigation structure and populate it across the entire site.