# js Function Button Load more..

****JS Button Load more****


### Including files:

```html
<script src="../dist/btnloadmore.min.js"></script>
```

## How to use

you need to do is call the plugin inside a $(document).ready function:

```javascript
$(document).ready(function(){
	$('.contents').btnLoadmore();
});
```

## Options

```javascript
$('.contents').btnLoadmore({
	showItem : 2,
        whenClickBtn : 1,
	textBtn : 'Load more ...'
});

```
