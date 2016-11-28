## Readme

This Jekyll Blog Template is based on [jekyll-cayman-theme](https://github.com/pietromenna/jekyll-cayman-theme)

and Plugins:

* [jekyll-table-of-contents](https://github.com/ghiculescu/jekyll-table-of-contents)

### Improved

1. Add **Tag** feature
2. Add **toc** for post

> this 2 features are critical for a **complete** blog system

### 1 Setup

1.1 \_config.yml

> Modify all `TODO`

1.2 Install

```bash
# under root folder
bundle install

# local run
jekyll serve
```

### 2 Example

[Chen Blog](http://chen-node.com/)

#### 2.1 Index page

![](https://github.com/neilChenXie/jekyll-cayman-theme-improved/blob/master/public/image/README/example.png)

#### 2.2 Table of Content on the left side

![](https://github.com/neilChenXie/jekyll-cayman-theme-improved/blob/master/public/image/README/example2.png)

#### 2.3 Tag Cloud page

![](https://github.com/neilChenXie/jekyll-cayman-theme-improved/blob/master/public/image/README/example1.png)

### 3 Folder structure

#### 3.1 Template

> Only related to template, won't effect all wrote posts.

##### 3.1.1 Page construct

* `_includes`
* `_layouts`

##### 3.1.2 Static

> no need to explain

* `js`
* `css`

##### 3.1.3 Tag&Category page

* `categories`

	> Category index page

* `tags`

	> Tag index page

#### 3.2 Site related

> different from site to site

* `public`
* `_posts`
* `_tages_page`

	> Collection page for each tag	

