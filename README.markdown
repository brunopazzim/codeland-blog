## CodeLand Blog

This is the main app used to generate and publish posts to the CodeLand blog.

## Blogging basics

1. Clone the repository
2. Create your post by running rake new_post["Yout Post Title"]
3. Edit your post on _posts/ with the following:
```---
author: Your name
layout: post
title: "Yout Post Title"
date: AAAA-MM-DD HH:MM
comments: true
categories:
  - Category 1
  - Category 2
---
Yout post content goes here
```
4. Execute rake generate preview
5. Access localhost:4000/blog on your browser and review your post
6. If everything is allright, commit your post with git commit -m 'Post: Your Post Title'
7. Just push it all up!

And we're done :)
