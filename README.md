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
	<seriously-effect type="pixelate" pixelSize="{{pixelSize}}"></seriously-effect>
	<seriously-effect type="blur" amount=".5"></seriously-effect>
	<seriously-target width="411" height="425"></seriously-target>
</seriously-graph>

```


TODO
=====

- docs mentioning loading of effects. Same way Seriously does it.
- test some complex node graphs
- test multiple node graphs
- browser compatibility tests
- seriously-graph.export() -> vanilla js

[1]:https://github.com/brianchirls/Seriously.js
[2]:http://polymer-project.org

NOTES
=====

- Firefox doesn't fire mutationChange handler when nodes are deleted from dev tools inspector.