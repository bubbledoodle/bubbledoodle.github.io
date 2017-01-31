---
layout: post
section-type: post
title: Title
category: Category
tags: [ '折腾', 'tech', 'front-end' ]
---

# HELLO WORLD
Build this blog is like takes me about one day but few other days to enjoy it. To make it more meaningful than how currently it is, I dicided to post this very first blog.

## A walk through of blog establishment. 
I did a search on finding a cheap, fancy, easy way to create a website and enables all features needed to build a personal blog on it. Turns out I found [jekyll](https://jekyllrb.com) and [github page](https://pages.github.com), which create static web pages and pushes and hosted on github. Also I actually found something interesting talking about [static vs dynamic website](http://nilclass.com/courses/what-is-a-static-website/#1), which is certainly next step work gonna include.

Here are some basic introducing blog list below. 

1. [intro example (chinese version)](http://pizida.com/technology/2016/03/03/use-jekyll-create-blog-on-github/)
2. [Another intro (chinese version)](http://xjliao.me/2013/03/19/jekyll-github.html)

For the first blog, there is a gap between transfer from jekyll generated sample page to actually published gitpage. It is very easy to get lost in jekyll and github relations. For the second, I used it for finding a way to change the theme, while jekyll default generated page got a very ugly theme. Changing the theme actually took me tones of time.

All in one sentence: __Here are some of difficulties I met during the entire procedure:__

1. gitpage clone into local repo, then what? serve jekyll in git repo dir?
2. how can I change the theme? following gem instructions always report error and that does not feel good.
3. I need a special domain name, link it to github page.
4. certificate fails, turns out gitpage does not support https when using custom CNAME

All those difficulties from least understanding of certain idea. Follows the instruction does not help, while basic idea could be difficult to get too. In this blog will only talk about those how I solved those difficulties.


