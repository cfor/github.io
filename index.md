---
title       : Simple Metric Converter
subtitle    : 
author      : Clem O'Rourke
job         : Assignment 1
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---
<h2>  Metric Converter (p2)</h2>

Here is my metric converter.  It is only a start.



But I'm sure you will see it's potential
       



---
<h2>  Metric Converter (p3)</h2>

So far we can convert 
<li>Centimetres to Inches </li>
<li>Kilograms to pounds </li>

A pull down box is used to select either Length or Mass. 
A slider is used to specify the number of units. 

Length uses a multiplier of 0.393700787 
For example, if the slider value is 10 then 

```r
10*0.393700787
```

```
## [1] 3.937
```

---
<h2>  Metric Converter (p4)</h2>

Mass uses a multiplier of 2.20462 
thus, if the slider value is 10 then 

```r
10*2.20462
```

```
## [1] 22.05
```


---
<h2>  Metric Converter  (p5)</h2>



<h3>  There is lots more to do</h3>
<h3>  There are also lots of converters available</h3>
    so just perhaps not a super future - but
<h2>  It has been a tremendous introducton to</h2>

<li> R </li>
<li> RStudio </li>
<li> Shiny </li>
<li> Slidify </li>
