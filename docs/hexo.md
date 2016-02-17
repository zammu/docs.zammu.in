# How to deploy a Hexo website

You can now setup your Zammu websites to be built using the awesome [Hexo](https://hexo.io) static site generator now.

In this short post I'll show you how to get your Hexo website built on GitHub Pages automatically for each git push using [Zammu](https://zammu.in).

 1. Sign up for [zammu.in](https://zammu.in) using GitHub.
 2. Create a new site using the "Hexo" generator and enter the github url of your hexo website e.g. *zammu/hexo.zammu.in* with the other details.
 3. That's it. Now you whenever you push to your github repository, your website will be built using Hexo and will be published to GitHub Pages on subdomain.zammu.in

- - -

**Here are some commands used to setup your repository**

~~~bash
# init the new site
hexo init awesome-hexo-blog

# init the repo
cd awesome-hexo-blog
git init
git commit -m 'init'

# now we need to go to github and create our repository and then
git remote add origin git@github.com:minhajuddin/awesome-hexo-blog
git push origin master -u

# now we need to go to https://zammu.in and create a new site with the following  info
# Generator = Hexo
# Title = My awesome Blog
# Domain =
# Subdomain = awesomehexo
# GitHub URL = minhajuddin/awesome-hexo-blog

echo "That's it we are done"
~~~

