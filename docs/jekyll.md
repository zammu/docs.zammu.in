title: How to setup automatic build and deploy for a jekyll blog on github pages using zammu
date: 2016-01-27 16:52:07
tags:
  - Github Pages
  - Jekyll
---

In this blog post I'll show you how to setup Automatic Deployment of Jekyll on Github Pages using Zammu.

  1. Setup Jekyll and add a Gemfile
    ~~~sh
    gem install jekyll
    jekyll new my-awesome-blog
    ~~~
  2. Setup a Gemfile. This step is very important.
    ~~~sh
    echo 'source "https://rubygems.org"' >> Gemfile
    echo 'gem "jekyll"' >> Gemfile
    ~~~
    Once you are done with this step you should have a Gemfile with the following content:
    ~~~ruby
    source "https://rubygems.org"
    gem "jekyll"
    ~~~
  3. Push it to a Github Repository.
  4. Log in to https://zammu.in and create a new site using the "Jekyll" generator

That's it. Now you can start creating new posting just by adding content and pushing to Github.

### You can use the invitation code `JEKYLLROCKS` to signup on https://zammu.in/jekyll?invitation_code=JEKYLLROCKS
