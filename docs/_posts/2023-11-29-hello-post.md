---
title:  "Hello Post"
search: true
categories: 
  - Jekyll
last_modified_at: 2018-02-19T08:06:00-05:00
---

This post should not appear in the search index because it has the following YAML Front Matter:


### A post

Hello _(Post)_ World

```yaml
algolia:
  # Exclude more files from indexing
  files_to_exclude:
    - index.html
    - index.md
    - excluded-file.html
    - _posts/2017-11-28-post-exclude-search.md
    - subdirectory/*.html
```