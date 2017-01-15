- To publish a post write it here in `org-mode` and then export it
  to`dev/ccann.github.io/_posts` via `C-c C-e` then `P x` and `blog`. See configuration
  in `init.el`.
- This blog uses Jekyll 3, that's it!
- you need htmlize.el installed and the htmlize package installed on your machine to
  support highlighting syntax on export.
  
- Seems that you now need:

``` text
#+BEGIN_EXPORT html
---
layout: post
title: blah
tags: foo bar
---
#+END_EXPORT
```






