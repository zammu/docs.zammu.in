# How to setup automatic build and deploy for a jekyll blog on github pages using zammu

In this blog post I'll show you how to setup Automatic Deployment of Jekyll on Github Pages using Zammu.

### Setup Jekyll and add a Gemfile
~~~sh
gem install jekyll
jekyll new my-awesome-blog
~~~

### Setup a Gemfile. This step is very important.
~~~sh
echo 'source "https://rubygems.org"' >> Gemfile
echo 'gem "jekyll"' >> Gemfile
~~~

### Once you are done with this step you should have a Gemfile with the following content:
~~~ruby
source "https://rubygems.org"
gem "jekyll"
~~~

### Push it to a Github Repository.
### Log in to https://zammu.in and create a new site using the "Jekyll" generator

That's it. Now you can start creating new posting just by adding content and pushing to Github.
