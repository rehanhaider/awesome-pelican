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
* [Resources](#resources)
* [Plugins](#plugins)
* [Themes](#themes)
* [Projects using Pelican](#projects-using-pelican)
* [Articles & Guides](#articles--guides)
* [Contributing](#contributing)

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
\# | Plugin/GitHub | PyPI Version | Author | Description
---- | ---- | ---- | ---- | ----
1 | [image-process](https://github.com/pelican-plugins/image-process) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-image-process)](https://pypi.org/project/pelican-image-process/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that automates image processing 
2 | [seo](https://github.com/pelican-plugins/seo) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-seo)](https://pypi.org/project/pelican-seo/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin to improve search engine optimization (SEO) 
3 | [sitemap](https://github.com/pelican-plugins/sitemap)| [![PyPI Version](https://img.shields.io/pypi/v/pelican-sitemap)](https://pypi.org/project/pelican-sitemap/) | [pelican-plugins](https://github.com/pelican-plugins) | Generates a site map for Pelican-powered sites 
4 | [pelican-algolia](https://github.com/rehanhaider/pelican-algolia) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-algolia)](https://pypi.org/project/pelican-algolia/)| [rehanhaider](https://github.com/rehanhaider) |  Plugin to integrate Algolia Search with Pelican SSG
5 | [tag-cloud](https://github.com/pelican-plugins/tag-cloud) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-tag-cloud)](https://pypi.org/project/pelican-tag-cloud/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that generates a tag cloud from post tags 
6 | [similar-posts](https://github.com/pelican-plugins/similar-posts) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-similar-posts)](https://pypi.org/project/pelican-similar-posts/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin to list similar posts to articles, based on a vector space model
7 | [series](https://github.com/pelican-plugins/series) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-series)](https://pypi.org/project/pelican-series/) | [pelican-plugins](https://github.com/pelican-plugins) | Series is a Pelican plugin that joins multiple posts into a series 
8 | [webassets](https://github.com/pelican-plugins/webassets) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-webassets)](https://pypi.org/project/pelican-webassets/)| [pelican-plugins](https://github.com/pelican-plugins) | Use the webassets module to manage assets such as CSS and JS files
9 | [avatar](https://github.com/pelican-plugins/avatar) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-avatar)](https://pypi.org/project/pelican-avatar/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that adds Libravatar or Gravatar user profile pictures
10| [share-post](https://github.com/pelican-plugins/share-post) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-share-post)](https://pypi.org/project/pelican-share-post/) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that creates privacy-friendly URLs for sharing the current article 
11 | [neighbors](https://github.com/pelican-plugins/neighbors) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-neighbors)](https://pypi.org/project/pelican-neighbors/)| [pelican-plugins](https://github.com/pelican-plugins) |  Neighbors is a Pelican plugin that adds Next/Previous links to articles 
12 | [simple-footnotes](https://github.com/pelican-plugins/simple-footnotes) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-simple-footnotes)](https://pypi.org/project/pelican-simple-footnotes/) | [pelican-plugins](https://github.com/pelican-plugins) |  Adds footnotes to articles and pages 
13 | [liquid-tags](https://github.com/pelican-plugins/liquid-tags) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-liquid-tags)](https://pypi.org/project/pelican-liquid-tags/) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that supports Liquid-style tags in Markdown 
14 | [photos](https://github.com/pelican-plugins/photos) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-photos)](https://pypi.org/project/pelican-photos/) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that adds photos to articles
15 | [webring](https://github.com/pelican-plugins/webring) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-webring)](https://pypi.org/project/pelican-webring) | [pelican-plugins](https://github.com/pelican-plugins) |  Display latest posts from a list of feeds on your site 
16 | [jinja-filters](https://github.com/pelican-plugins/jinja-filters) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-jinja-filters)](https://pypi.org/project/pelican-jinja-filters) | [pelican-plugins](https://github.com/pelican-plugins) | Provides a selection of functions (called filters) for templates to use when building your website
17 | [more-categories](https://github.com/pelican-plugins/more-categories) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-more-categories)](https://pypi.org/projectpelican-more-categories) | [pelican-plugins](https://github.com/pelican-plugins) |  Enables nested categories and multiple categories per article 
18 | [render-math](https://github.com/pelican-plugins/render-math) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-render-math)](https://pypi.org/project/pelican-render-math) | [pelican-plugins](https://github.com/pelican-plugins) | | Pelican plugin that renders mathematics via the MathJax JavaScript engine 
19 | [jinja2content](https://github.com/pelican-plugins/jinja2content) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-jinja2content)](https://pypi.org/project/pelican-jinja2content/) | [pelican-plugins](https://github.com/pelican-plugins) |  Use Jinja2 template code within post content 
20 | [pandoc-reader](https://github.com/pelican-plugins/pandoc-reader) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-pandoc-reader)](https://pypi.org/project/pelican-pandoc-reader) | [pelican-plugins](https://github.com/pelican-plugins) |  Pandoc Reader is a Pelican plugin that processes Markdown content via Pandoc 
22 | [linkbacks](https://github.com/pelican-plugins/linkbacks) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-plugin-linkbacks)](https://pypi.org/project/pelican-plugin-linkbacks) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin implementing Linkback protocols, on the linking server side. 
23 | [related-posts](https://github.com/pelican-plugins/related-posts) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-related-posts)](https://pypi.org/project/pelican-related-posts) | [pelican-plugins](https://github.com/pelican-plugins) |  Related Posts is a Pelican plugin that adds a list of related posts to an article
24 | [thumbnailer](https://github.com/pelican-plugins/thumbnailer) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-thumbnailer)](https://pypi.org/project/pelican-thumbnailer) | [pelican-plugins](https://github.com/pelican-plugins) | Thumbnailer is a Pelican plugin that creates image thumbnails in various sizes
25 | [feed-filter](https://github.com/pelican-plugins/feed-filter) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-feed-filter)](https://pypi.org/project/pelican-feed-filter) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that filters elements from feeds 
26 | [linkclass](https://github.com/pelican-plugins/linkclass) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-linkclass)](https://pypi.org/project/pelican-linkclass) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin to set anchor tag's class attribute to differentiate between internal and external links 
27 | [share-post](https://github.com/pelican-plugins/share-post) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-share-post)](https://pypi.org/project/pelican-share-post) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that creates privacy-friendly URLs for sharing the current article 
28 | [nojekyll](https://github.com/pelican-plugins/nojekyll) | [![PyPI Version](https://img.shields.io/pypi/v/minchin.pelican.plugins.nojekyll)](https://pypi.org/project/minchin.pelican.plugins.nojekyll) | [pelican-plugins](https://github.com/pelican-plugins) | Pelican plugin that adds a `.nojekyll` file to the output root. Useful for publishing to Github Pages. Written in Python
29 | [graphviz](https://github.com/pelican-plugins/graphviz) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-graphviz)](https://pypi.org/project/pelican-graphviz) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that renders Graphviz images from Markdown content 
30 | [read-more](https://github.com/pelican-plugins/read-more) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-read-more)](https://pypi.org/project/pelican-read-more) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that inserts an inline "Read More" link into the last HTML element of the summary 
31 | [image-preview-thumbnailer](https://github.com/pelican-plugins/image-preview-thumbnailer) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-plugin-image-preview-thumbnailer)](https://pypi.org/project/pelican-plugin-image-preview-thumbnailer) | [pelican-plugins](https://github.com/pelican-plugins) |  Pelican plugin that insert thumbnails along image links 
32 | [show-source](https://github.com/pelican-plugins/show-source) | [![PyPI Version](https://img.shields.io/pypi/v/pelican-show-source)](https://pypi.org/project/pelican-show-source) | [pelican-plugins](https://github.com/pelican-plugins) |  Link to the source text of your posts 

<!--
Use the below template
x | [github name](https://github.com/<link>) | [![PyPI Version](https://img.shields.io/pypi/v/<plugin-name>)](https://pypi.org/project/<plugin-name>) | [pelican-plugins](https://github.com/<author>) |  Desription
-->

## Themes

* Official [Pelican Theme Repository](https://github.com/getpelican/pelican-themes)
* [Pelican Theme Gallery](http://www.pelicanthemes.com/)

### **Open Source Pelican Themes**
\# | Theme/GitHub | PyPI Version  | Author | Demo
---- | ---- | ---- | ---- | ----
1 | [Flex](https://github.com/alexandrevicenzi/Flex/) | NA | [Alexandr Vicenzi](https://github.com/alexandrevicenzi) | [flex.alxd.me](https://flex.alxd.me/)
2 | [Elegant](https://github.com/Pelican-Elegant/elegant) | NA | [Pelican Elegant](https://github.com/Pelican-Elegant) | [elegant.oncrashreboot.com/](https://elegant.oncrashreboot.com)
3 | [Seafoam](https://github.com/MinchinWeb/seafoam) | [![PyPI Version](https://img.shields.io/pypi/v/seafoam)](https://pypi.org/project/seafoam) | [MinchinWeb](https://github.com/MinchinWeb) | [minchin.ca](http://minchin.ca/)
4 | [Atilla](https://github.com/zutrinken/attila) | NA | [Zutrinken](https://github.com/zutrinken) | [https://attila.peteramende.de](https://attila.peteramende.de/)
4 | [Octopress](https://github.com/duilio/pelican-octopress-theme) | NA | [Duilio](https://github.com/duilio) | [Demo](http://blogs.skicelab.com/maurizio/)

## Powered By Pelican

Projects built with pelican

1. [Apache.org](https://apache.org/)
2. [Full Stack Python](https://www.fullstackpython.com/): [(GitHub repo)](https://github.com/mattmakai/fullstackpython.com)
3. [CloudBytes/Dev>](https://cloudbytes.dev): [(GitHub repo)](https://github.com/CloudBytesDotDev/CloudBytes.dev)
4. [Bottlepy](http://blog.bottlepy.org/) : [(GitHub repo)](https://github.com/bottlepy/bottle)
5. [This Week in Rust](http://this-week-in-rust.org/) : [(GitHub repo)](https://github.com/rust-lang/this-week-in-rust)
5. [Easylist.to](https://easylist.to/)

## Articles & Guides


## Contributing

