---
title: "Modifying the handbook"
tags: [handbook]
# keywords: release notes, announcements, what's new, new features
last_updated: September 24, 2020
# summary: ""
sidebar: mydoc_sidebar
permalink: modifying_the_handbook.html
folder: handbook
toc: off
---

   You can modify or edit the content of a page directly on Github. For this you will first need to login (or signup if you do not have an account yet)to Github.     
       {% include image.html file="/github_login.png" alt="" caption="" %}


### Edit your content and make a pull request:
  
  1. After you have logged into Github go to the page you want to edit on the website. On the page click on the GitHub icon which states *Edit me*.The “Edit me”
     icon will take you to the GitHub repository, where you again click on the pencil icon, shown on the right, and start editing.
  
       {% include image.html file="/github_edit2.png" alt="" caption="" %}

  2. You can now edit or add new text and images required for the content you want to add. Formatting is done according the MkDocs format 
     [Cheathseet](http://madrus4u.com/mdocs/engine/cheatsheet/).
     
  3. When you are happy with the edited content, go to the “Propose changes” section at the end of the page and write a title and a brief 
     explanation of your changes.This can be as short as ‘fixing a typo’, ‘mkdocs formatting issue’ or be more elaborate explaining what section was added and why.
  
  4. Click on “Propose changes”.
    {% include image.html class="mt-0 mb-0" file="propose_changes_github.png" inline=true alt="Propose changes on GitHub" %}
  
  5. You are now redirected to the Pull Request (PR) page. A "pull request" is a request to "pull" your changes into the website. 
     Click on the "Create Pull Request" green button. Here you can choose to:

      - "Create draft pull request": choose this if you have not finished writing. Later on you can always click on "Ready for review" to switch to a normal 
         pull request. You can find more information about draft pull requests in the [GitHub documentation](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests#draft-pull-requests).
      - "Create pull request": choose this if you have finished your text. Editors will then review your request.
         {% include image.html class="mt-0 mb-0" file="draft_pullrequest_github.png" inline=true alt="PrDraft pull request on GitHub" %}

  6. In case you created a "draft pull request", you can return to your pull request by going to the [pull request section](https://github.com/ibisba/handbook/pulls) of our GitHub repo.
  
  7. If you open a normal pull request then a review is automatically requested. The relevant editors will check your changes. 

### Address editors' comments

 1. When editors add comments or add a review of your pull request, you will be notified.
 2. You need to address editors' comments and requests by editing your pull request as in step 5 (see above).
      - Go to your pull request
      - Click on "Files changed" in the top menu bar.
        {% include image.html class="mt-0 mb-0" file="files_changed_github.png" inline=true alt="Files changed tab on GitHub" %}
      - Click on the icon with 3 dots "..." of the file you  want to edit and then click on "Edit file".
        {% include image.html class="mt-0 mb-0" file="3_dots_github.png" inline=true alt="File change options on GitHub" %}
      - Make your changes.
      - Click on “Commit changes”.
3. When all the requests have been addressed, the editors will mark the conversation as "Resolved" and the proposed changes as "Approved".
4. You content is ready to be merged and published in the main website.
5. Editors will publish your content.
