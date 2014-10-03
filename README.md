DEPreLoad.js
=========

Include this in your page in `<head>`, or before `</body>`:

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="jquery.DEPreLoad.js"></script>
```

Initialize the plugin within document ready function:

```javascript
$(document).ready(function() {
    var loader = $("body").DEPreLoad({
        OnStep: function(percent) {},
        OnComplete: function() {}
    });
});
```
