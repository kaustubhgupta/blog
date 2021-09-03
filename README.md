![blog](https://socialify.git.ci/kaustubhgupta/blog/image?description=1&descriptionEditable=All%20my%20nontech%20articles%20that%20were%20published%20on%20Wix%20are%20reposted%20here.%20Now%20onwards%2C%20non-tech%20articles%20will%20be%20published%20under%20this%20website.&forks=1&issues=1&language=1&owner=1&pulls=1&stargazers=1&theme=Light)

# [blog.kaustubhgupta.me](https://blog.kaustubhgupta.me/)

A Jekyll-themed blog website powered by Ruby and GitHub Pages. The website is configurable via `config.yml`. All my nontech articles that were published on Wix are reposted here. Now onwards, non-tech articles will be published under this website.

![image](./assets/images/screenshot.png)

## Local Run
```bash
jekyll serve
```

## Adding New Author

All the relevant details with respect to the Author can be added in the `config.yml` file under the `Authors` section.

## Adding New Blog Post
- `_posts` folder holds all the blogpost content
- Each file has to be named as `YY-MM-DD-title-in-.md`
- Every post markdown file should have the following configuration table at the top:

```
---
layout: post
title:  "Title"
author: author-name
categories: [cat1, cat2, ...]
image: assets/thumbnails/<image-name-with-extension>
comments: true/false
---
```

## Gallery

![img1](./assets/readmeImages/1.png)

![img1](./assets/readmeImages/2.png)

## License

[![MIT Licence](https://img.shields.io/github/license/kaustubhgupta/blog)](https://choosealicense.com/licenses/mit/)