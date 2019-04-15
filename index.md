# Publishing a website or software documentation with GitHub Pages now requires far fewer steps — three to be exact:

    Create a repository (or navigate to an existing repository)
    Commit a Markdown file via the web interface, just like you would any other file
    Activate GitHub Pages via your repository’s settings

And that’s it — you now have a website. If you’re already familiar with GitHub Pages, you may be interested to know that behind the scenes, we’re now doing a few things to simplify the publishing experience and bring it more in line with what you may expect from authoring Markdown content elsewhere on GitHub:

    All Markdown files are now rendered by GitHub Pages, saving you from needing to add YAML front matter (the metadata at the top of the file separated by ---s) to each file.
    We’ll use your README file as the site’s index if you don’t have an index.md (or index.html), not dissimilar from when you browse to a repository on GitHub.
    If you don’t specify a theme in your site’s config (or don’t have a config file at all), we’ll set a minimal, default theme that matches the look and feel of Markdown elsewhere on GitHub.
