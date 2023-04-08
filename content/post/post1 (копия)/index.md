---
title: Markdown

# Summary for listings and search engines
GitHub is the largest web service for hosting IT projects and their joint development. The web service is based on the Git version control system and developed on Ruby on Rails and Erlang by GitHub, Inc.:

# Link this post with a project
projects: []

# Date published
date: '2023-03-18T00:00:00Z'

# Date updated
lastmod: '2023-03-18T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - Darina Shiyapova

tags:
  - Academic
  - git

categories:
  - git

---



## Cisntaxis
A paragraph is one or more consecutive lines of text separated by one or more blank lines. If a string contains only spaces or tabs, it is still considered empty.

## Headline
Markdown offers two styles of writing headings: through lattices (#) and through underscores (====). You can use up to six levels of headers, but underscores allow you to create only the first two (<h1> and <h2>).

## Underscores (Setextstyle)
"Underlining" a paragraph with equal signs (=) or hyphens (-) makes it a first- or second-level heading, respectively. The level of the header depends only on the type of "dashes", their number does not matter.

There should be no empty lines between the text and the "underline".

## Lists
To create bulleted (numbered) lists, put a minus (-), plus (+) or an asterisk (*) before each item. The marker and the text of the item must be separated by a space.
If there are different markers in front of consecutive items, then after conversion we will get different lists.
Ordered

If we use numbers with a dot at the end (1., 2., etc.) as markers, then we will get an ordered (numbered) list.
The item numbers in the final markup will go in order (1, 2, 3), even if there will be 1., 4., 9 in Markdown.. This feature allows us to use "lazy numbering" when the same number is placed before each item.
The number before the first item shows where to start numbering the list items, so if you put 99., 1., 2. in Markdown, then in the final markup the items will be numbered 99, 100, 101.

Released under the [MIT](https://github.com/wowchemy/wowchemy-hugo-themes/blob/master/LICENSE.md) license.
