---
layout: post
title: Setup Jekyll on Github Pages
lead: A short test post to describe this setup.
---


# Free Hosting on Github

This is covered in several other places including on [Github's](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll) and [Jekyll's](https://jekyllrb.com/) pages. The idea is to host a simple static site with only to cost of a domain registration (optional).

To start, get a Github account. Try not to register it using your hotmail username that you created back in college like I did. Next create a repository called [username].github.io. Replace [username] with whatever your Github username. You can then push a simple hello world in the contents of an index.html file, navigate to https://[username].github.io and see if it works. If its not working, make sure you matched your username exactly. 

Next head over to [Jekyll's installation guide](https://jekyllrb.com/). You will need to first install Ruby, and then run the commands below for a slightly more impressive hello world.

```
gem install bundler jekyll
jekyll new my-awesome-site
cd my-awesome-site
bundle exec jekyll serve
# => Now browse to http://localhost:4000 
```
Once you've figured out what you want, you can view various themes linked from Jekyll's site. In my case, I went with [cvless](https://jamstackthemes.dev/theme/jekyll-cvless/). To use, clone it, and then replace the contents of your [username].github.io with what you just pulled down. Be sure to leave the .git files in place though. 