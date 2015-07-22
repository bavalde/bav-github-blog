---
layout: post
title: "Starting a New Github Blog"
modified:
categories: posts
excerpt:
tags: [info blog]
image:
  feature:
date: 2015-07-22T17:03:56+02:00
---

It´s summer and I have some free time so starting a new github blog. Yay! Slightly scary as I have 
never used github (or git) for anything serious before - I use svn and mercurial at work.
Anyways, how hard can it be? So let´s dive in.

##Setup so far

- The blog is created using [Jekyll](http://jekyllrb.com/) - a static site generator. I order to use this
you must have [Ruby](https://www.ruby-lang.org/en/) with the Ruby [gem](https://rubygems.org/) package manager installed.
- Found a Jekyll theme that looked nice from Michael Rose (thanks!), see the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/theme-setup/) repo.
- Following the theme instructions I have forked and renamed the repo as [https://github.com/bavalde/bav-github-blog.git](https://github.com/bavalde/bav-github-blog.git)
- I must have made a mistake when deleting and then creating a new gh-branch (idea was to start
with a clean working copy) because git started barfing at me so I did a hard reset origin -> gh-pages. 
- getting Jekyll and friends installed and working was very easy: "sudo gem install bundler" followed 
by "bundle install" and as far as I can see it´s just working.
- I´m writing this on a fairly recent osx-upgraded Mac, but github claimed my git was old so I grabbed a new 
git from [https://git-scm.com/](https://git-scm.com/). Seems strange, but whatever, I´m fine with that if you need me to.
- This setup was all done in a few minuttes (excluding reading/understanding time) and to build and view the sample site is 
as easy as "jekyll build" and/or "jekyll serve". 
- I´m not into serious vim (so far I have only learned enough vim to do basic editing when required). I guess an editor
with git integration would be nice and I´m trying out Microsofts [Code](https://code.visualstudio.com/) editor - looks nice so far. 
I´m sure there are alternatives, but it looks like a faster perhaps less crashy ;) Atom editor for me and with a nice Visual Studio feel.
- The site/blog as such needs a **major cleanup**, currently there are many demo posts and leftovers from the
repo I cloned, sorry about that, but the basics seems to be up and running. 
- As I´m writing this I have Jekyll serving in a Terminal window 
and every time I save an edited file the site is automatically updated (re-built) and can be viewed as localhost:4000. 
I think I can get used to this, pretty slick workflow.

##Summary
Basically, this setup was faster and easier than I could have imaged. I´m impressed with the Jekyll and ruby/gem utils
and to me the theme from Michael Rose looks pretty nice.

##Next Steps
Now I´m going the eat a macrell. What a booring fish and it´s all over the place for the time beeing. 
I wich it was a proper cod or something. Then I might actually write a proper blogpost.