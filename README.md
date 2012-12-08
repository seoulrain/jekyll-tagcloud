#Jekyll tag cloud (without plugins)

`jekyll-tagcloud` is a little hack to create a tag cloud and their respective 
posts for your [Jekyll] generated site hosted in GitHub Pages, using Liquid
and JavaScript (without plugins).
`jekyll-tagcloud` uses a linear logarithmic (very simple) in order to weight tags.
(A logarithmic assessment would be better).

Of course you can do the same using Jekyll plugins, but that means that
you would have to run Jekyll locally and post the produced files into your repo
(because GitHub Pages does not allow Jekyll plugins). I don't like that solution, 
hence `jekyll-tagcloud`.

See demo: http://enrmarc.github.com/tags.html  

[Jekyll]: https://github.com/mojombo/jekyll 
