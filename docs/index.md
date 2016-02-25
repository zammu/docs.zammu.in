# Setup your domain

You can setup your website on your domain using the following 3 simple steps:

  1. Create your website and set the domain in zammu to your desired domain,
      e.g. the blog minhajuddin.com is hosted on zammu, here is a screenshot of
      the 'edit site' page:
      ![Edit site](/images/domain-setup/edit-site.png)

  2. This step varies based on your deployment target:
    1. **GitHub Pages Naked domain (example.com)**  
      Go to your DNS provider's control panel and create two **A** records pointing to
      `192.30.252.153` and `192.30.252.154`.
      You can read more about it at https://help.github.com/articles/setting-up-an-apex-domain/
    2. **GitHub Pages or Amazon S3 CNAME (www.example.com)**  
      Go to your DNS provider's control panel and point your `www` CNAME record
      to your zammu subdomain, you can check the zammu subdomain in your site
      details page, the following is a screenshot of my blog's zammu details
      page, in my instance I could have pointed **www.minhajuddin.com to
      minhajuddin.zammu.in**
      ![Zammu subdomain](/images/domain-setup/zammu-subdomain.png)

That's it now your website should be up on your domain.
