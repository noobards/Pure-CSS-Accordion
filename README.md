# Pure-CSS-Accordion
An accordion which works without javascript. Yes, you read that right. 0% Javascript, 100% CSS

## Features
- [x] No javascript involved
- [x] Lightweight (~ 4kb)
- [x] Conforms to W3C Standards for HTML5 and CSS3

## Dependencies
None. All you need is a browser and you're good to go

## Browser Support
- IE9 and above
- Firefox
- Chrome
- Safari
- Opera

## Usage
```HTML
<!DOCTYPE html>
<html lang="en-us">
<head>
<meta charset="utf-8" />
<title>Accordion</title>
<link href="css/nl-accordion.css" rel="stylesheet" type="text/css" />
</head>
<body>
<div id="myAccordion" class="nl-accordion">
		<ul>
			<li>
				<input type="radio" id="nl-radio-1" name="nl-radio" class="nl-radio" />
				<label class="nl-label" for="nl-radio-1">Title&nbsp;One</label>
				<div class="nl-content">
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse nec posuere lorem. Pellentesque hendrerit, lorem luctus porttitor vestibulum, eros sapien mattis libero, euismod congue neque nisi at ipsum. Mauris semper ipsum sit amet metus semper malesuada. Donec vel est justo, ac porta diam.</p>
				</div>
			</li>
			<li>
				<input type="radio" id="nl-radio-2" name="nl-radio" class="nl-radio" />
				<label class="nl-label" for="nl-radio-2">Title&nbsp;Two</label>
				<div class="nl-content">
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse nec posuere lorem. Pellentesque hendrerit, lorem luctus porttitor vestibulum, eros sapien mattis libero, euismod congue neque nisi at ipsum. Mauris semper ipsum sit amet metus semper malesuada. Donec vel est justo, ac porta diam.</p>
				</div>
			</li>
			<li>
				<input type="radio" id="nl-radio-3" name="nl-radio" class="nl-radio" />
				<label class="nl-label" for="nl-radio-3">Title&nbsp;Three</label>
				<div class="nl-content">
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse nec posuere lorem. Pellentesque hendrerit, lorem luctus porttitor vestibulum, eros sapien mattis libero, euismod congue neque nisi at ipsum. Mauris semper ipsum sit amet metus semper malesuada. Donec vel est justo, ac porta diam.</p>
				</div>
			</li>
			<li>
				<input type="radio" id="nl-radio-4" name="nl-radio" class="nl-radio" />
				<label class="nl-label" for="nl-radio-4">Title&nbsp;Four</label>
				<div class="nl-content">
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse nec posuere lorem. Pellentesque hendrerit, lorem luctus porttitor vestibulum, eros sapien mattis libero, euismod congue neque nisi at ipsum. Mauris semper ipsum sit amet metus semper malesuada. Donec vel est justo, ac porta diam.</p>
				</div>
			</li>
		</ul>
</div>
</body>
</html>
```

## Instructions/Explanation
- Your root/parent container should have a class named `nl-accordion`
- Each `<li>` becomes an accordion panel. It contains:
  - A radio input with unique id and same name. Add the class `nl-radio` to it
  - A label to show the title of the accordion panel. Add the class `nl-lable` to it
  - A div that houses the content of the active panel. Add the class `nl-content` to it
 
## License
Code licensed under [GPL-3.0](https://github.com/noobards/Pure-CSS-Accordion/blob/master/LICENSE)

