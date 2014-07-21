Jekyll-OCRA
===========

Windows portable executable of Jekyll, made with OCRA.
No external dependencies needed (if you don't need pygmentize).

Current standalone is built against jekyll-2.1.1, and comes _as is_.
It was built for my own needs (tm).
Serving, building and watching a jekyll directory should work just fine.

Compiled with:
```
> ocra --console jekyll-2.1.1/bin/jekyll jekyll-2.1.1/lib/jekyll/mime.types jekyll-2.1.1/lib/site_template/**/* jekyll-2.1.1/lib/site_template/*
```

Credits: 
[Nick Williams](http://www.nickw.it/jekyll-dot-exe/)
