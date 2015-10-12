## Website Performance Optimization portfolio project

Moved essential CSS to HTML header.
Minified internal CSS using http://cssminifier.com/
Deleted two external CSS files (no longer needed)
Minified remaining external CSS files using http://cssminifier.com/
Minified JS file using http://jscompress.com/
Added personal google analytics tracking number
Compressed image files.
Specified images' widths and heights.
Removed unnecessary font style.
Deleted unnecessary HTML pages.
Used media queries for CSS files.
Removed white-space and comments from HTML.
Added Cache-control meta tag (<meta http-equiv="Cache-control" content="max-age=600, public">).
Moved JavaScript to end of HTML body.
For pizza.html:
	restructured entire page
	minified style.css using http://cssminifier.com/
	eliminated approximately 20% of the JS from external file
	added in-text JS in order to provide button functionality
	changed scrolling pizzas to moving pizzas using CSS keyframes
	did not minify internal CSS in order to allow for its review
	made a scrolling div to house pizza combinations generated by JS
	time to generate pizzas on load: 18.92ms
	fps is never greater than 45


