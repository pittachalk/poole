---
layout: post
title: Plotly Template Slide
description: This is a description for the template slide.
---
### Simple instructions
You can include a plotly HTML figure with the `include_relative` macro. Here are a few things to take note of:

* This allows you to include things that are not necessarily in the `_includes` subdirectory.
* The relative path must be in relation to this file, thus in the relevant subdirectory of the `_posts` directory in this case. You cannot use `../`.


#### Simple example
{% include_relative figure.html %}

Notice that the length is constrained by whatever was set in Plotly.

#### For PNG and SVG
Use the classic Markdown syntax.

```
![alternate text](img_path "hover_text")
```

![Alternate text](figure.svg "SVG title which shows when hoevered across")

![Alternate text](figure.png "PNG title which shows when hoevered across")

Note that PDF does not work.

### External reading
Read more [here](https://jekyllrb.com/docs/includes/).

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Image title which shows when hoevered across")

```py
print("Thank you for reading.")
```

