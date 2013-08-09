---
layout: post
title:  "Textile Examples"
date:   2013-07-29 11:16 PM
categories: markdown
---

This is strictly markdown examples.
I have [textile][2] and [Pygments with Liquid tags][3] examples on the other pages.

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6


* this is bullet
* this is another bullet


Multiple levels

* this is main
    * this is sub level
        * this is third level



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


**This is bold**
*This is italic*

[this is regular link](http://www.google.com)

[this is referenced link][1]
the reference links can be found at the bottom of the code.




this is inline `code block` which I think really cool with this theme.

this will give me formatted ruby code
{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

this is the code with line numbers
{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}



[1]: http://www.google.com
[2]: http://www.google.com
[3]: http://www.google.com