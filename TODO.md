implement picture element instead background image

example
<picture>
	<source media="(max-width: 460px)" srcset="./images/image-product-mobile.jpg">
	<img src="./images/image-product-desktop.jpg" alt="{your alt text goes here}">
</picture>