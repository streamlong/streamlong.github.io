## Summary

This repo is an extraction from [archive.org](https://archive.org) for [dreamhead.blogbus.com](http://dreamhead.blogbus.com)

## Jekyll

* this repo uses [jekyll](https://jekyllrb.com) with [mediumish-theme-jekyll](https://github.com/wowthemesnet/mediumish-theme-jekyll/), run `bundle exec jekyll serve` to view in browser
* with the MARKDOWN files under *_posts*, it can be transfered to other themes/tools of your choice

## Parser

* raw data extracted is saved in *posts.json*
* markdown template can be modified in erb template file (*post_template.erb*)
* run `./parse_posts` to regenerat markdown files from source `posts.json` after you change template file

## Copyright

* Copyright of all posts in this repo belongs to the author of [dreamhead.blogbus.com](http://dreamhead.blogbus.com)


## 2020.01.17 

* 从gzzengwei/dreamhead-blogbus-archive Fork 项目到自己的仓库，更改自己的仓库名称，这样就不需要本地环境安装各种环境，就可以成功访问

* 之前clone源代码到本地后，因为语言初次接触，环境配置各种坑，导致一致都没有成功，今天偶然发现通过fork的方式，完美解决，yeah！
