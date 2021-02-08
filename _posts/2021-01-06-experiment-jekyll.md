---
layout: post
title: Introducing Jekyll to this page
heading: "Experiment: Jekyll"
categories: Project
---
Since 2 years I am operating this blog as pure HTML, CSS and a little bit of JavaScript, first on an Apache webserver, then on Github Pages. Recently a friend asked, if there would be a RSS feed for my blog, since he finds my [cynical glossary](/category/cynical-glossary/index.html) a cool idea. I didn't have one ([I have one now](/feed.xml)), so I did a little bit of research about RSS in general and then I stumbled across Jekyll (again). I knew that Github Pages supports Jekyll themes natively, but never gave it a try. It seemed easy to generate a RSS feed automatically with the plugin [Jekyll feed](https://github.com/jekyll/jekyll-feed), so I gave it a try. First I had some difficulties to set Jekyll up locally, I think due to some Ruby versioning issues, so I started by just pushing my Jekyll code to Github. I could see changes quickly in case the compiled, but destroyed my blog if they didn't, so.. I needed to get it running locally soon.  
  
But first, I wanted to experiment more. The [documentation of Jekyll](https://jekyllrb.com/docs/) is really good and readable to get started, and I found it quite easy to set everything up. I extracted my blog posts into seperate files markdown and html files, that are named after a certain pattern and located in a certain folder. Jekyll then understands that those texts are blog posts, and enables quite a lot of cool features for blogging such as the RSS feed plugin, I just had to turn it on. One aspect I particularly liked about Jekyll was the usage of [liquid](https://shopify.github.io/liquid), which provides conditions, loops and variables/objects for HTML. For example: Instead of repeating HTML for the title of a blog post, I could simply extract that and use the variables of my page object:

        <h1>
            <a href="{{'{{'}} page.url }}">{{'{{'}} page.title }}</a>
        </h1>

I put this in a loop, together with the heading, text and signature of the post, and immediately all blog posts were rendered the expected way below each other. Jekyll generates static HTML out of the liquid HTML, so that it can be deployed on a static webserver. **Liquid feels like improved HTML.** I worked a couple of days (not consistently) on the transition of my blog to Jekyll, and now I have some handy new features, that were easy to build, add and/or configure:
- [The requested RSS feed](/feed.xml), subscribe if you don't want to miss any post, [read this](https://en.wikipedia.org/wiki/RSS) if you want to know what it is
- Blog posts have categories
- Blog posts can be filtered by category, just use the categories listed [at the top](https://robertnickel.online/blog.html), or click on the category in the signature of the post
- Blog posts have static urls (e.g. [https://robertnickel.online/2021/01/06/experiment-jekyll.html](https://robertnickel.online/2021/01/06/experiment-jekyll.html)), just click on the title of a post to go there.
- I removed the "Projects" area, since it is a category now, that can be used as a filter

Conclusion: Jekyll is very lightweight, for example in comparision with WordPress. It is incredibely well documented and easy to start with (just push something to Github Pages). The terminology is intuitive and the usage of liquid enabled me to not repeat myself and have a scalable solution (in terms of adding content, categories, rss etc.). **I recommend it!**

**EDIT:** Right after publishing this post I realized, that [Github Pages only supports certain plugins for Jekyll](https://pages.github.com/versions/) natively. Therefore, I had two options:
1. Revert the category pages related changes and not use the plugin.
2. Keep using the plugin and avoid using the Github Pages native Jekyll by just refering to the generated static code.
   
I chose to go with option 2 and found out that I have to create a folder called /docs in order to make it referable as document root for Github Pages. Since I want to avoid having multiple repos or branches, I then created a git pre-commit hook that copies all the files from the generated /_site folder into the /docs folder (which is refered to as document root). I find it odd, that I cannot define custom folders, since I would rather have named it "static" or similar. Anyway... using unsupported plugins should now be fine again. 🙂