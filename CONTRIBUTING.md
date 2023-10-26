# Contributing to the project

## Content

There are three main ways to contribute content to this project:

1. Use the CMS to create a block directly
2. Open a PR to create a block directly
3. Open an issue to ask someone else to create something

### Use the CMS

To use the CMS, you need an account. This access is limited to CYF members. Join the PD team to get access. Once you have an account, you can log in at https://cyf-pd.netlify.app/admin.

### Open a PR

1. Create a new folder in /content/blocks
2. Include the required front matter, eg:

```md
+++
title = ""
description="Short 30 word description of the block"
modules = ["Fundamentals", "HTML-CSS", "JS1", "JS2", "JS3", "React", "Node", "Databases", "The Launch", "Portfolios"]
week = [1, 2, 3, 4]
skills = ["Professional", "Confidence", "Communication", "Time Management", "Employability"]
[objectives]
    1="Write a failing test"
time = 60
prep = ""
introduction = "markdown content max 100 words"
[[exercises]]
name = "exercise1"
time = 20
goal = "markdown content max 50 words"
content = "markdown content max 100 words"

[[exercises]]
name = "exercise2"
time = 20
goal = "markdown content max 50 words"
content = "markdown content max 100 words"
+++
```

And write your post in markdown.

3. Open a PR with your post

Please follow the PR template. If you are not sure how to do this, open a new issue and someone will review your submission.

### Open an issue

If you are not sure how to create a post, or you don't have access to the CMS, you can open an issue. Someone will review your submission.

## Development

This is a microsite. It is not intended to be a general purpose website. We are not interested in adding features that are not directly related to the purpose of the site, which is a streamlined cms for the PD volunteers to develop the CYF PD curriculum and make it available to be consumed by other CYF products.

If you want to contribute to the development of the site, please open an issue to discuss your idea. We are happy to accept PRs for bug fixes and small improvements, but we need to discuss larger changes first.

To run the site locally, you need to install Hugo. See the README for more details.
