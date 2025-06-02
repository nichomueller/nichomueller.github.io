<!--
Add here global page variables to use throughout your website.
-->

@def bibliography = "/assets/references.bib"

+++
author = "Nicholas Mueller"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Nicholas Mueller website"
website_descr = "Nicholas Mueller website"
website_url   = "https://nichomueller.github.io"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\doi}[1]{[DOI:#1](https://dx.doi.org/#1)}
\newcommand{\challenge}[2]{@@challenge @@title **!#1**@@ @@content #2 @@ @@}