# seriously.polymer

[Polymer components][2] for [Seriously.js][1]

http://positlabs.github.io/seriously.polymer/

Do `bower install` to grab dependencies.


Use declaritive magic to create Seriously.js node graphs! Woah!

```html
<seriously-graph linear>
	<seriously-source>
		<img src="images/pencils.jpg">
	</seriously-source>
	<effect-pixelate pixelSize="{{pixelSize}}"></effect-pixelate>
	<effect-blur amount=".5"></effect-blur>
	<seriously-target width="411" height="425"></seriously-target>
</seriously-graph>

```


TODO
=====

- docs mentioning loading of effects. Same way Seriously does it.
- test multiple node graphs
- browser compatibility tests
- seriously-graph.export() -> vanilla js

[1]:https://github.com/brianchirls/Seriously.js
[2]:http://polymer-project.org

