jquery-insetborder
=====================

Inset border effect easy and simple.

Support
=======
From oldest to newest versions of the common browsers, such as: chrome, firefox, safari, opera............ IE.

Important?
==========

Sure, inset border is a pretty effect, but can be a pain in the ass because involve measure movement.

Usage
=====

Just call the plugin at the element you want to add a inset border effect.

```
$(document).ready(function(){

	$('a').borderEffect();
	
});
```

How it work?
============

The plugin add position:relative to the element that will receive the border, and append a </div> with position:absolute, this </div> have a border-width effect that not move the content, easing the work of do a inset border effect.