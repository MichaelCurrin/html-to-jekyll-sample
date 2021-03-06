# HTML to Jekyll Sample ๐ ๐งช
> A demo to showcase converting a plain HTML site to a Jekyll site

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/html-to-jekyll-sample?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/html-to-jekyll-sample/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Ruby](https://img.shields.io/badge/Ruby->=2.6-blue?logo=ruby&logoColor=white)](https://ruby-lang.org)
[![Made with Jekyll](https://img.shields.io/badge/Jekyll-3.9-blue?logo=jekyll&logoColor=white)](https://jekyllrb.com)

[![Hosted with GH Pages](https://img.shields.io/badge/Hosted_with-GitHub_Pages-blue?logo=github&logoColor=white)](https://pages.github.com/)


## Preview

_Note this site is not finished yet - the navbar is not set up right, but the styling and page structure is setup_.

<div align="center">
    <a href="https://michaelcurrin.github.io/html-to-jekyll-sample/">
        <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="400" />
    </a>
</div>


## Use this project

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/html-to-jekyll-sample/generate)

[![View site - GH Pages](https://img.shields.io/badge/View_site-GH_Pages-blue?style=for-the-badge)](https://michaelcurrin.github.io/html-to-jekyll-sample/)

</div>


## Tutorial

This explains how I create this project as a new Jekyll site, starting from an HTML site.

For intetest, see also the [HTML to Jekyll](https://jekyllrb.com/tutorials/convert-site-to-jekyll/) tutorial in the Jekyll docs.

### YouTube video

My intention was to take an existing site with content and styling and build a Jekyll site out of it.

I hosted a live session on YouTube to do just that. It is available as a recording.

- [Jekyll live coding](https://www.youtube.com/watch?v=6v5vEBUmkGs)

This repo was created from scratch in that session. I encourage you to watch that video and compare it with this repo.

### Choose an HTML base

I found this article of 99 free HTML templates.

- [99 Free HTML Templates You Can Download Right Now](https://html.com/resources/free-html-templates/)

The first option on that list is this CodePen, which I liked.

- [Asperion HTML5 template](https://codepen.io/alexdevero/pen/GCirD) by [Alex Devero](http://alexdevero.com) / [@alexdevero](https://github.com/alexdevero).

So I used that for the tutorial.

It has "template" in the name, so I feel comfortable that the creator indended the code to be reused by others.

### Uploaded repo

I cleaned up the code after the live session and uploaded it as this repo. This is a demo or sample which supplements the tutorial video.

I also copied the rendered content to [sample.html](/sample.html) as well to make it easier to compare the Jekyll site against it and in case the pen disappears.


## Related projects

A example of a Jekyll site also with no theme, based on a tutorial in the Jekyll docs (linked so you can follow the steps too):

- [Jekyll Themeless Quickstart](https://github.com/MichaelCurrin/themeless-jekyll-quickstart)

If you are interested in a Jekyll site with a theme, see:

- [Jekyll Blog Demo](https://github.com/jekyll-blog-demo)
    - A typical Jekyll site that has minimal basic functionality and a theme and is served on on GH Pages
- [Jekyll Themed Site Quickstart](https://github.com/MichaelCurrin/jekyll-themed-site-quickstart)
    - A site with few files that demonstrates using a theme on a GH Pages site.

If want to build your own theme and then install it in another project of yours, or let the Jekyll community use your theme, see:

- [Jekyll Theme Quickstart](https://github.com/MichaelCurrin/jekyll-theme-quickstart)


## Installation

Clone the repo.

Install Ruby and Bundler globally.

Install project gems.

```sh
$ make install
```


## Usage

Start dev server.

```sh
$ make serve
```

Do a production build and output as `_site` directory.

```sh
$ make build
```


## Deploy

1. Get a copy of this repo on GitHub.
2. Go to _Setting_ for your repo, _Pages_ and then enable GitHub Pages on the main branch on the root path.
3. Wait for your site to build.
4. Check the _Environment_ tab and find the URL for your site.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
