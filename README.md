# Js-Slider

This JavaScript file contains:

#### 1. An object named pictures
and
#### 2. a function named Slider.


__The object__ describes some slides.
Each slide consists of attributes such as _img_url,heading,summary_
etc that refer to the content and other like _fontsize,height,
color_ etc that refer to the styling.
There are a few attributes that determines the way the
slideshow behaves(_fadein_ or _toleft_) as well.
There can be as many slides as we want.

__The Slider__ function consists of two other functions:  
_createDom_ and _slideShow_.  
The first one creates the HTML that we need for our slider and  
the second one determines the way our slider should behave.

The Slider function takes two parameters:
  
* the element name,   
is the name of a variabale which value is the html element tag  
that contains the slideshow   
and     
* the configuration object,  
which contains all the information we need about the slides(in our 
case pictures).
