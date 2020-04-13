### HTML Chapter 16

* By default, images are inline elements. They flow with the surrounding text.  
* To center an image, it should be a block-level element `display: block;`  
* The background-image property allows you to place an image behind any HTML element. By default, a background image will repeat to fill lthe entire box.  
* If you don't want it to repeat, use `background-repeat: no-repeat;` and if you want the image to stay in place use `background-attachment: fixed;` otherwise use `background-attachment: scroll;`  
* Background shorthand  
```
body{
    background: #ffffff url("images/tulip.gif") no-repeat top right;}
```
This order must be followed:  
1. background-coor
1. background-image
1. background-repeat
1. background-attachment
1. background-position

* You can use a gradient as a backgrond image as well.  

### HTML Chapter 19

* Search engine optimization is the practice of trying to help your site appear nearer the top of search results. It is split into:  
1. <b>On-page Techniques</b> - Including keywords in t he text and HTML code.  
1. <b>Off-page Techniques</b> - Getting other, relevant websites to link to your site.  

* Use (www.google.com/analytics) to analyze how people found your website.  
* You'll need a FTP to transfer code from your computer to the hosting company. For example, FileZilla.  

### MDN Article on Audio and Visual Elements

* HTML has `<video>` and `<audio>` elements.  
* The whole player is wrapped in a `<div>` tag.     
* The `<video>` element contains two `<source>` elements to accomodate different browser.  


