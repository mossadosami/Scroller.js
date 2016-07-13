#Scroller.js v1
by Mosaad Osami

The only 2K file and the easiest Way ever to animate your page on scroll!

NO hassel NO wierd stuff, 
just add ONE attribute to animate your page on Scroll.


##What it's all about
This just do the job, add animation to the HTML elements on Scroll 
depending on Animate.css and jquey.

##Why it's that simple
because you need only two steps:

Add these links to your page <head>
<link rel="stylesheet" href="http://s.mlcdn.co/animate.css">
<script src="https://code.jquery.com/jquery-2.2.4.js"></script>
<script src="https://cdnjs.cloudflare.com/Scroller.js"></script>
Add attribute moel-ani-data= and its values as below. 
<h1 moel-ani-data="fadeInUp after-1s for-1s" ></h1>
##How to Customize?
Only in three steps:

Animation type
you can use all class on Animate.css
<h1 ... moel-ani-data="fadeInUp ..." ></h1>
Animation delay (start animation after 1 sec or 2 sec ...)
<h1 ... moel-ani-data="...after-1s ..." ></h1>
Check the other options:
after-0-5s
after-1s
after-1-5s
...
after-5-5s
Animation duration
<h1 ... moel-ani-data="...for-1s" ></h1>
Check the other options:
for-0-5s
for-1s
for-1-5s
...
for-5-5s
##Upcoming features Super Awesome version 1.5! yay
Now it's only entrance version (On page load, elements is hidden then appears and animates by scroll). The next existence version the element is not hidden by default, the scroll triggers the animation itself on existed element.
Using multiple animations and time options on the same element.
