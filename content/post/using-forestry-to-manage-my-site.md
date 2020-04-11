+++
authors = []
categories = []
date = 2020-04-10T22:00:00Z
draft = true
featured = false
lastmod = ""
math = false
projects = []
subtitle = "Do I need it?"
summary = "forestry.io provides a user-friendly web-interface to manage static web sites. The question is whether this is easier than creating and editing the pages from IDE?"
tags = ["website"]
title = "Using forestry to manage my site"
[image]
caption = "Editing web site with forestry"
focal_point = ""
highlight_languages = ""
preview_only = false

+++
After entering forestry.io, granting them access to the source repo of website and performing initial setup, I've got an environment where I can create and edit posts. There is an opportunity to preview the post, and all the post meta-fields can be filled in here.

This difference is minimal. It might be helpful for a company web-site, where the users should not bother about `git commit` _etc._

I was not able to create a post as page bundle, maybe there should be some other template used, but I didn't find it. In addition, every time I press **Save draft,** a new commit is created? This might make the repo history unreadable (in case anyone would ever want to read it).

There is however one good thing---I can use Grammarly tool to check my English. :smiley: 

So my conclusion is -- it's a good tool, and because of Grammarly, I might use it from time to time for "postprocessing".

Update: forestry might be also very helpful to edit posts from a mobile device. For the changes in source to become visible in the published site, an automated deployment should be arranged in some way.