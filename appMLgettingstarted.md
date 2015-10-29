# appML getting started #


**1)** Download appML (http://code.google.com/p/appml/)

**2)** Make sure you include the necessary scripts in your page:


&lt;link rel="stylesheet" href="MobileAppStyle.css"/&gt;




&lt;style type="text/css" media="all"&gt;

@import "themes/apple/theme.css";</
style>
<script type="text/javascript" charset="utf-8" src="js/jquery/
jquery-1.4.4-hicVersion.js">

Unknown end tag for &lt;/script&gt;


<script type="text/javascript" charset="utf-8" src="js/jQueryUI/jquery-
ui-1.8.5.custom.min.js">

Unknown end tag for &lt;/script&gt;


<script type="text/javascript" charset="utf-8" src="js/pluginJquery/
livequery/jquery.livequery-1.0.3.js">

Unknown end tag for &lt;/script&gt;


<script type="text/javascript" charset="utf-8" src="js/hicTech/
appManager.js">

Unknown end tag for &lt;/script&gt;


note: jquery-1.4.4-hicVersion.js is jquery-1.4.4 with a little
modification on line 2280, where we simply add changedTouches property
to jQuery Event object, as follow:
props: "altKey attrChange attrName bubbles button changedTouches
cancelable charCode clientX......
We are always in touch with jQuery releases: appML will always include
last jQuery stable version, so don't worry, be happy! ;-D

**3)** Make sure your HTML has an 

&lt;appml&gt;

 tag element:


&lt;appml&gt;


> 

&lt;loading&gt;



&lt;/loading&gt;


> 

&lt;content&gt;


> .
> .
> .
see some example:
http://www.appml.org/documentation.html#example