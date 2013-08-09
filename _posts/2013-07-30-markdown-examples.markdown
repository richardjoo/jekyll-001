---
layout: post
title:  "Markdown Examples"
date:   2013-07-29 11:16 PM
categories: markdown
---

This is strictly markdown examples.
I got many contents from [wiki][4].

I have [textile][2] and [Pygments with Liquid tags][3] examples on the other pages.

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6



This is different way to show first-level heading
=======================================

This is different way to show second-level heading
---------------------------------------  
  
  

To insert a linebreak,  
end a line with two or more spaces followed by a return.   

For example (using visible space notation):  
here is line one then press space bar twice and hit return.

this is first line, and to line break  hit enter  
and type something else.


* this is bullet
* this is another bullet


Multiple levels

* this is main
    * this is sub level
        * this is third level
        * You can use + or - too
        + this is another sub level
        - this is sub level too!



This is number bullets

1. numbered
2. two
3. three
4. four


This is numbered bullets with sub items

1. numbered
    1. sub 1
    2. sub 2
2. two
    1. sub 1
    2. sub 2
3. three
    * combo
    * comb 2
4. four


If blank lines are placed between items, they will be parsed as paragraphs. Multi-paragraph list items can be created by indenting the paragraphs by 4 spaces or 1 tab.

* Item 1
    
    I got the one line down and 4 spaces to create multiple paragraphs here.  As you can see, this will shows up as paragraph

    And this one as another paragraph too!

* Item 2
* Item 3


*emphasis (italic)* or _emphasis (italic)_

**strong emphasis (boldface)** or __strong emphasis (boldface)__

***very strong emphasis (italic and boldface)*** or ___very strong emphasis (italic and boldface)___ 


**This is bold**
*This is italic*

[this is regular link](http://www.google.com)  

[this is referenced link][1]
the reference links can be found at the bottom of the code.




this is inline `code block` which I think really cool with this theme.

Multiline code or longer pieces of code should be indented by four spaces.

    code line 1
    code line 2
    code line 3



Blockquotes are created by adding an angle bracket. For example:

> "This entire paragraph of text will be enclosed in an HTML blockquote element.
Blockquote elements are reflowable. You may arbitrarily
wrap the text to your liking, and it will all be parsed
into a single blockquote element."



### Links:
You have few options to do links  
[this is a link](http://www.google.com)  
[this is a link too][url_ref]  


### Image
this is an animated gif  
````
  ![this is an animated gif]({{ site.url }}/images/9DSZf.jpeg)
````

![this is an animated gif]({{ site.url }}/images/9DSZf.jpeg)


this works too

![Alt text][image_1]

[image_1]: {{ site.url }}/images/9DSZf.jpeg  "Optional title attribute"


### Horizontals

* * *
***
*****
- - -
---------------------------------------






[1]: http://www.google.com
[2]: http://www.google.com
[3]: http://www.google.com
[4]: http://en.wikipedia.org/wiki/Markdown
[url_ref]: http://www.google.com

