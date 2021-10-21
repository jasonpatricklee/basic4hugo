---
title: "About this theme"
date: 2021-09-10T19:04:33-07:00
draft: false
tags: about
description: Overview of the theme's offerings and how to use it.
---

### Why?

Quickly publish your content with Hugo's features of Markdown processing, and this theme's ease of use. Writing becomes easier with a system that is easier to manage and post to; this Hugo theme makes things as barebones as possible.

To use the styling and elements listed below, you follow the simple [syntax of Markdown](https://www.markdownguide.org/basic-syntax/). This page is auto generated from a Markdown (.md) file.

### Unordered lists

- unordered lists
- second item

### Ordered lists

1. ordered lists
2. second item

### Blockquotes and Callouts

> Blockquotes look like this with all of the text after the &gt; symbol in Markdown. These are good for a light emphasis

### Code

Similar to the blockquotes, but with monospace and scrollable formatting. You can also easily add [syntax highlighting](https://gohugo.io/content-management/syntax-highlighting/). 

```
def dfs(visited, graph, node):  # function for dfs
    if node not in visited:
        print (node)
        visited.add(node)
        for neighbour in graph[node]:
            dfs(visited, graph, neighbour)

def print_stuff():
    x = "hey"
    print('this content is all scrollable if it gets overflowed')
    print('the code is all between two sets of ``` in markdown')
    return x
```
### Emphasis

This is **bolded text** and this is *italicized text*.

### Images

![A house with clouds behind it during a winter sunset in Tacoma, Washington](/img/house.jpg)
