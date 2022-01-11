
@def prepath = "fmiki_web"
@def website_title = "fmiki's website"
@def author = "fmiki"
@def mintoclevel = 2

@def ignore = ["node_modules/", "franklin", "franklin.pub"]

<!--
Add here global page variables to use throughout your website.
-->
+++
author = "fmiki"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "fmiki's page"
website_descr = "fmiki"
website_url   = "https://pseudorangex.github.io/web_fmiki/"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
