# MkDocs

We'll setup the awesome [MkDocs](http://www.mkdocs.org) documentation generator to Continuously Build and Deploy your documentation in this article.


 1. Go to the *New Site* page and select the **Python and Pip**
 2. On the second page, fill out the necessary details. Fill `mkdocs build` for the build command and `site` for the output directory
 3. Make sure your git repository has a `requirements.txt` file with the following contents  
        ```
        mkdocs>=0.15.2
        ```

That's it you are all set for Continuous Delivery of your documentation site. The icing on the cake is that **others can now contribute to your documentation project via GitHub**.
e.g. You can try out contributions by creating a pull request on this very documentation site (Yes, it is built using MkDocs :) ). Just click on the 'Edit on GitHub' button in the top left corner.
