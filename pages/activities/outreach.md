---
layout: page
subheadline:  "Activities"
title:  "Outreach"
teaser: "Introducing the next generation to the exciting world of science!</a>."
categories:
    - design
tags:
    - post format
image:
   thumb: "activities/2019_gmsd_siobhan.jpg"
gallery:
    - image_url: activities/2019_gmsd_siobhan.jpg
      caption: Learning about genome assembly with Legos
    - image_url: activities/2019_gmsd_christina.jpg
      caption: Learning about genome assembly with Legos
    - image_url: activities/2017_gmsd_nick.jpg
      caption: Learning to code by guiding their friends through a maze
    - image_url: activities/2017_gmsd_sahra.jpg
      caption: Learning to code by guiding their friends through a maze

---


{% include gallery %}


## How to embed a gallery

`{% raw %}{% include gallery %}{% endraw %}` lets you easily embed a gallery into your post. To use the gallery-include...


### Step 1

1. Make two images: a thumbnail and a big image.
2. Name the thumbnail *gallery-image-thumb.jpg* and...
3. ...name the big *gallery-image.jpg*.
4. Place them in the *images*-folder.


### Step 2

Define the big version in frontmatter,  

~~~
gallery:
    - image_url: gallery-image.jpg
~~~

If you like captions, give each image a caption:

~~~
gallery:
    - image_url: gallery-image.jpg
       caption: Starting Page with huge One Logo
~~~

### Step 3

Add the include whereever you want in your content with `{% raw %}{% include gallery %}{% endraw %}`.

{% include alert info='Have a look at this example-entry. And have a look into the images-folder. :)' %}







