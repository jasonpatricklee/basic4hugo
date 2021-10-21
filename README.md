# Basic for Hugo

Keep the focus on writing. 

1. Start by making sure you have [Hugo](https://gohugo.io) and [git](https://git-scm.com) installed.
2. `cd DESIRED_SITE_LOCATION`
3. `hugo new site SITE_NAME`
4. `cd SITE_NAME`
5. `git init`
6. `git submodule add https://github.com/iasonlee/basic_hugo.git themes/basic`
7. take folder basic and put it into themes directly (not tested)
8. add `theme = 'basic'` and change baseURL to `baseURL = '/'` in config.toml 
9. delete the filler content in themes/basic/content/Words and change the index and titles
10. create your first post `hugo new Words/title.md`
11. test the site at `DESIRED_SITE_LOCATION/SITE_NAME` with `hugo server`
