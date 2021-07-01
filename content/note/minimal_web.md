---
title : "Making Webpage Serve Faster"
subtitle : "Tweaks done to serve this website faster"
showInHome : True
date : 2021-06-27
---
            
The philosophy I am trying to follow: "Use it when you need it!"

Earlier I used to spent eternity redesigning this website. It is just like decorating your house. But with time I realized that it is not worth the time and resources. It was making this website slower and bandwidth eater.

Now I want to keep everything simple and fast. I have followed the below step to improve this site :

## Removal of javascript

Javascript is an awesome language. But on this website, there is no need for javascript.
 
## Removal of div tags

HTML5 is bundled with so many functional tags like main, article, section, header, footer, etc. Using those native tags is always a good option over div tags. 

It won't improve or decrease any performance, but it will make code clean and clutter-free.

## Removal of CSS class

Tailwind or bootstrap CSS frameworks mostly depend on css class files for UI elements. But class files are not mandatory. We can use it directly via tag element for every tags.
i.e.

instead of 

        <p class="colorblue"> Demo text </p>

        colorblue {
                color: blue
        }

use this

        <p> Demo text </p>

        p {
                color: blue
        }

## Use of webp and svg

Image format webp, a new image format that provides lossless and lossy compression for the web, and supports transparent images too.

SVG is also very compressible and lightweight; An image quality remains high regardless of the compression rate.
