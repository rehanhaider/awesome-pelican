# Awesome Pelican

A curated list of awesome things related to Pelican, the most popular static site generator written in Python.

Pelican’s feature highlights include:

* Articles (e.g., blog posts) and pages (e.g., "About", "Projects", "Contact")
* Integration with external services
* Site themes (created using [Jinja2](https://palletsprojects.com/p/jinja/) templates)
* Publication of articles in multiple languages
* Generation of Atom and RSS feeds
* Code syntax highlighting
* Import existing content from WordPress, Dotclear, or RSS feeds
* Fast rebuild times thanks to content caching and selective output writing
* Extensible via a rich plugin ecosystem: [Pelican Plugins](https://github.com/pelican-plugins)

### Why the name “Pelican”?

“Pelican” is an anagram for calepin, which means “notebook” in French. ;)


## Contents


## Resources

### Official

* [Quickstart](https://docs.getpelican.com/en/latest/quickstart.html)
* [Pelican on GitHub](https://github.com/getpelican/pelican)
* [Website](https://getpelican.com/)
    * [Documentation](https://docs.getpelican.com/)
    * [News](https://getpelican.com/news/)
    * [Blog](https://getpelican.com/blog/)
* [New Official Plugins GitHub](https://github.com/pelican-plugins)
* [Old Plugins Monorepository - NOT MAINTAINED](https://github.com/getpelican/pelican-plugins)

## Plugins

### Migrated to new architecture
# | Plugin | Author | Description
---- | ---- | ---- | ---- 
1 | [image-process](https://github.com/pelican-plugins/image-process) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that automates image processing 
2 | [seo](https://github.com/pelican-plugins/seo) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin to improve search engine optimization (SEO) 
3 | [sitemap](https://github.com/pelican-plugins/sitemap) | [pelican-plugins](https://github.com/pelican-plugins) |  Generates a site map for Pelican-powered sites 
4 | [render-math](https://github.com/pelican-plugins/render-math) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that renders mathematics via the MathJax JavaScript engine 
5 | [similar-posts](https://github.com/pelican-plugins/similar-posts) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin to list similar posts to articles, based on a vector space model
6 | [jinja2content](https://github.com/pelican-plugins/jinja2content) | [pelican-plugins](https://github.com/pelican-plugins) |  Use Jinja2 template code within post content 
7 | [neightbors](https://github.com/pelican-plugins/neighbors) | [pelican-plugins](https://github.com/pelican-plugins) |  Neighbors is a Pelican plugin that adds Next/Previous links to articles 
8 | [simple-footnotes](https://github.com/pelican-plugins/simple-footnotes) | [pelican-plugins](https://github.com/pelican-plugins) |  Adds footnotes to articles and pages 
9 | [webassets](https://github.com/pelican-plugins/webassets) | [pelican-plugins](https://github.com/pelican-plugins) |  Use the webassets module to manage assets such as CSS and JS files 
10 | [pandoc-reader](https://github.com/pelican-plugins/pandoc-reader) | [pelican-plugins](https://github.com/pelican-plugins) |  Pandoc Reader is a Pelican plugin that processes Markdown content via Pandoc 
11 | [webring](https://github.com/pelican-plugins/webring) | [pelican-plugins](https://github.com/pelican-plugins) |  Display latest posts from a list of feeds on your site 
12 | [tipue-search](https://github.com/pelican-plugins/tipue-search) | [pelican-plugins](https://github.com/pelican-plugins) | Serialize generated HTML content to a JS variable for use by the Tipue static search jQuery plugin 
13 | [pelimoji](https://github.com/pelican-plugins/pelimoji) | [pelican-plugins](https://github.com/pelican-plugins) | Pelimoji is a Pelican plugin that adds support for custom emoji to your site
14 | [linkbacks](https://github.com/pelican-plugins/linkbacks) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin implementing Linkback protocols, on the linking server side. 
15 | [liquid-tags](https://github.com/pelican-plugins/liquid-tags) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that supports Liquid-style tags in Markdown 
16 | [related-posts](https://github.com/pelican-plugins/related-posts) | [pelican-plugins](https://github.com/pelican-plugins) |  Related Posts is a Pelican plugin that adds a list of related posts to an article
17 | [photos](https://github.com/pelican-plugins/photos) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that adds photos to articles
18 | [jinja-filters](https://github.com/pelican-plugins/jinja-filters) | [pelican-plugins](https://github.com/pelican-plugins) | Provides a selection of functions (called filters) for templates to use when building your website
19 | [thumnailer](https://github.com/pelican-plugins/thumbnailer) | [pelican-plugins](https://github.com/pelican-plugins) | Thumbnailer is a Pelican plugin that creates image thumbnails in various sizes
20 | [feed-filter](https://github.com/pelican-plugins/feed-filter) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that filters elements from feeds 
21 | [mode-categories](https://github.com/pelican-plugins/more-categories) | [pelican-plugins](https://github.com/pelican-plugins) |  Enables nested categories and multiple categories per article 
22 | [linkclass](https://github.com/pelican-plugins/linkclass) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin to set anchor tag's class attribute to differentiate between internal and external links 
23 | [share-post](https://github.com/pelican-plugins/share-post) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that creates privacy-friendly URLs for sharing the current article 
24 | [series](https://github.com/pelican-plugins/series) | [pelican-plugins](https://github.com/pelican-plugins) | Series is a Pelican plugin that joins multiple posts into a series 
25 | [nojekyll](https://github.com/pelican-plugins/nojekyll) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that adds a `.nojekyll` file to the output root. Useful for publishing to Github Pages. Written in Python
26 | [tag-cloud](https://github.com/pelican-plugins/tag-cloud) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that generates a tag cloud from post tags 
27 | [avatar](https://github.com/pelican-plugins/avatar) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that adds Libravatar or Gravatar user profile pictures
28 | [pdf](https://github.com/pelican-plugins/pdf) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that saves articles and pages as PDF files 
29 | [graphviz](https://github.com/pelican-plugins/graphviz) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that renders Graphviz images from Markdown content 
30 | [read-more](https://github.com/pelican-plugins/read-more) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that inserts an inline "Read More" link into the last HTML element of the summary 
31 | [image-preview-thumbnailer](https://github.com/pelican-plugins/image-preview-thumbnailer) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that insert thumbnails along image links 
32 | [show-source](https://github.com/pelican-plugins/show-source) | [pelican-plugins](https://github.com/pelican-plugins) |  Link to the source text of your posts 

## Themes


## Projects using Pelican


## Articles & Guides


## Contributing

