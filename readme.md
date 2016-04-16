# MixInUp

##### Example HTML:

```html
	<div id="mix_container">
		<div class="mix category-1" data-my-order="1"> ... </div>
		<div class="mix category-1" data-my-order="2"> ... </div>
		<div class="mix category-2" data-my-order="3"> ... </div>
		<div class="mix category-2" data-my-order="4"> ... </div>
	</div>
	<button class="filter" data-filter=".category-1">Category 1</button>
	<button class="filter" data-filter=".category-2">Category 2</button>
```

##### List-grid Switcher:
```html
	<button class="sort" data-sort="my-order:asc">Ascending Order</button>
	<button class="sort" data-sort="my-order:desc">Descending Order</button>
```

##### In the main.js:
```javascript
	$('#mix_container').mixItUp();
```

##### In your css:
```css
#mix_container .mix{
	display: none;
}
```

##### Include jQuery and jquery.mixitup.min.js into the footer.

```html
<script type="text/javascript" src="js/jquery.mixitup.min.js"></script>
```

##### More options
https://mixitup.kunkalabs.com/docs/