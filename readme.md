#Classic Mint Green

It's a theme inherits from `classic` themes of `octopress`. We believe the classic theme of octopress already provides a fancy and useful layout, only a minor customization is required to obtain your own theme.

I like mint green. :)

#Installing the theme

```
$ cd your_octopress_dir
$ git submodule add https://github.com/SiNZeRo/classicmintgreen .themes/classicmintgreen
$ rake install['classicmintgreen']
$ rake generate
```

#Modification

1. max-width is changed to 1920px
2. add some features to `sass/custom/_style.css`
3. add category an tags cloud to aside(side bar)

To completely setup this feature, please refer to [octopress-tagcloud](https://github.com/tokkonopapa/octopress-tagcloud)

4. modify sass/custom/_color.css to obtain `mint green` view.

#Ongoing
1. I'm a fresh newbie of octopress. This theme was produced under many unreasonable trials. Thus, the framework may be changed in future. Anyone would like improve this theme is appreciate.
2. Customize disqus to remove ads.

