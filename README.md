Unmuter
==========

About this Plugin:
==========

A plugin for JW Player. Provides a highly visible "unmute" button for players that are initially muted.

Unmuter was originally created by Tony Boyd. 

I updated it to work with JW6, and fixed some minor issues with the plugin.

### [Demo](http://www.pluginsbyethan.com/github/unmuter.html)

Implementing this Plugin:
==========

There is one file that you need to use, unmuter.js. Upload this file to your server, it can go anywhere on the server. Now, inside of your JW Player embed code, make sure that your plugins call points to the full path to the .js file on your server (http://www.yoursite.com/unmuter.js).

Example:
==========

<pre>
&lt;div id=&quot;player&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
jwplayer('player').setup({
&nbsp;&nbsp;'primary':'flash',
&nbsp;&nbsp;'width': '575',
&nbsp;&nbsp;'height': '400',
&nbsp;&nbsp;'file': 'video.mp4'
&nbsp;&nbsp;'image': &quot;video.jpg&quot;,
&nbsp;&nbsp;plugins: {
	&nbsp;&nbsp;&nbsp;&nbsp;&quot;unmuter.js&quot;: {
	&nbsp;&nbsp;}
&nbsp;&nbsp;}
});
&lt;/script&gt;
</pre>

The source code is available for this plugin. There is just a .js file for JavaScript. Publishing the JavaScipt can be simply done with any text editor. Enjoy~! :) 