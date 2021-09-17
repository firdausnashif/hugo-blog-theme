---
summary: ""
authors:
  - admin
lastMod: 2019-09-05T00:00:00.000Z
title: Cara Setting Totolink N200RE Menjadi Repeater
subtitle: Cara mudah setting totolnk n200re menjadi repeater sebagai berikut
date: 2019-02-05T00:00:00.000Z
tags: []
categories: []
projects: []
image:
  caption: ""
  focal_point: ""
  filename: featured.jpg
---




![png](index_1_0.jpg)

## Langkah

<!--StartFragment-->

1. Pada menu Operation Mode pilih Repeater (range extender), Apply
2. Kemudian masuk ke menu Repeater Setup,

   * Pilih enable, 
   * Setting nama SSID, 
   *  Scan AP (scan ssid wifi yang akan di repeater), pastikan bisa konek
   * setting password  wifi repeater
   * Apply,

<!--EndFragment-->

```bash
mkdir -p <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
cd <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
jupyter lab index.ipynb
```

The `jupyter` command above will launch the JupyterLab editor, allowing us to add Academic metadata and write the content.

## Edit your post metadata

The first cell of your Jupter notebook will contain your post metadata ([front matter](https://sourcethemes.com/academic/docs/front-matter/)).

In Jupter, choose *Markdown* as the type of the first cell and wrap your Academic metadata in three dashes, indicating that it is YAML front matter: 

```
---
title: My post's title
date: 2019-09-01

# Put any other Academic metadata here...
---
```

Edit the metadata of your post, using the [documentation](https://sourcethemes.com/academic/docs/managing-content) as a guide to the available options.

To set a [featured image](https://sourcethemes.com/academic/docs/managing-content/#featured-image), place an image named `featured` into your post's folder.

For other tips, such as using math, see the guide on [writing content with Academic](https://sourcethemes.com/academic/docs/writing-markdown-latex/). 

## Convert notebook to Markdown

```bash
jupyter nbconvert index.ipynb --to markdown --NbConvertApp.output_files_dir=.
```

## Example

This post was created with Jupyter. The orginal files can be found at https://github.com/gcushen/hugo-academic/tree/master/exampleSite/content/post/jupyter