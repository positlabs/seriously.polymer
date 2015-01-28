# seriously.polymer
Polymer components for Seriously.js


Do `bower install` to grab dependencies.


Use declaritive magic to create Seriously.js node graphs! Woah!

```
<seriously-graph linear>
	<seriously-source>
		<img src="images/pencils.jpg">
	</seriously-source>
	<seriously-effect type="pixelate" properties="{{ {pixelSize: pixelSize} }}"></seriously-effect>
	<seriously-effect type="blur"></seriously-effect>
	<seriously-target width="411" height="425"></seriously-target>
</seriously-graph>

```