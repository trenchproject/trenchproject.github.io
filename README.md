# TrEnCh Project Website. 
[![Build Status](https://travis-ci.org/trenchproject/trenchproject.github.io.svg?branch=master)](https://travis-ci.org/trenchproject/trenchproject.github.io)

## Adding content. 
### Pages.
There are 3 steps to adding a new page to the Trench website. 

1. Create a new file in the `_pages` directory with the template `<pagename>.md`. 
2. Copy and paste the following into the top of your new file, substituting all placeholders for the particular information for the new page: 
```
---
permalink: <<insert permalink, like /people or /tools. this is optional, you can delete this line>>
title: <<insert title>>
author_profile: true
layout: single
header: 
    overlay_image: assets/images/ashcroft.jpg
---
```
3. Place the page's content as markdown-formatted text below the above content. 

When you `git add _pages/<newfile.md>` and commit and push, the page will be live at `http://trenchproject.github.io/<<pagename>>.html` or at `/<<permalink`, depending on whether you set a permalink. 

### Blog Posts. 
The process is similar for blog posts. 


1. Create a new file in the `_posts` directory with the filename `YYYY-MM-DD-title-of-post.md`. 
2. Copy and paste the following into the top of your new file, substituting all placeholders for the particular information for the new page: 
```
---
title: <<insert title>>
excerpt: <<optional short description of the post>>
---
```
3. Below that content, write the post as markdown-formatted text. 

Adding, committing, and pushing the above file to the repository will add the post to the list of posts at `http://trenchproject.github.io/news`, and the post will be accessible at `/news/post-title`. 
