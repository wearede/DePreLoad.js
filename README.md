DEload.js
=========

Include this in your page (in <head>, or before </body>):

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="jquery.DEload.js"></script>
```

Initialize the plugin within document ready function:

```javascript
$(document).ready(function() {

	var loader = $("body").DELoad({
		OnStep: function(percent) {
			console.dir(percent);
		},
		OnComplete: function() {
			console.dir('Done');
		}
		
}
```
