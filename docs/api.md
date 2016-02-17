title: Trigger your deploys using our brand new API
date: 2016-01-26 08:58:02
tags:
- API
- Automate
- Trigger Build
---

Today we have added the ability to trigger your deploys via our API.
You could do this to automatatically publish your draft pages at the end of each day.

To setup access via the API:

  1. Visit the site details page and click on the *API acess information* link.
      {% asset_img api-deploy1.png Link to API info %}
  2. Copy the curl code which includes your sites id, your api key and your api secret and run it on the terminal.
      {% asset_img api-deploy2.png Curl code which shows API usage %}
  3. Run it on your terminal
      {% asset_img api-deploy3.png Terminal with trigger code %}

**However, make sure that you keep the api_key and the api_secret safe**

If you end up exposing them, you can reset the api_key and api_secret from the users page.
      {% asset_img api_deploy4.png Reset API Key and Secret%}

P.S Don't try triggering any builds using these keys, I have reset my tokens ;)
