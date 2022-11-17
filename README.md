# wodin-news

This is the source for our wodin changelog, it will be deployed to https://reside-ic.github.io/wodin-news

## Install hugo

This needs a recentish version of hugo (at least 0.83), which might not get on with the current reside blog. The version in apt is probably too old, but snap works (`sudo snap install hugo --channel=extended`)

## Download source

```
git clone --recursive git@github.com:reside-ic/wodin-news
```

## Create a new post

```
hugo new posts/<title>
```

This will create a .md file in `content/posts` which you should edit.

The front matter options that might be useful:

```
---
title: "Add a title here"
date: 2022-10-20T13:51:48+01:00
tags: ["Feature"]
version: ["wodin v0.1.4"]
---
```

## Writing posts

Please include a tag in your post header using `tags: ["Feature"]`. Please use one of the following tags:
* Feature - a new feature that users have asked for or will notice
* Update - a smaller update to something in the UI, or a less user facing update change, or a change to logic
* App - a whole new app type

Include a version with the `version` field (e.g., `version: ["wodin v0.1.4"]`).

## Develop

```
hugo serve
```

Visit http://localhost:1313/wodin-news/ to see changes, editing the file will reflect immediately

## Docs

* [Theme docs](https://github.com/adityatelange/hugo-PaperMod)
* [Hugo docs](https://gohugo.io/documentation/)
