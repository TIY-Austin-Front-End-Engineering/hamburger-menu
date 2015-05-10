# Hamburger Menu

## Description
Create a mobile style hamburger menu using CSS and only two elements.


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand what CSS pseudo-elements are


### Performance Objectives

After completing this assignment, you be able to effectively use

* ::before
* ::after
* position relative
* position absolute



## Details

### Deliverables

* A repo containing at least:
  * `dist/style.css`
  * `dist/index.html`

### Requirements

* No legitimate W3C validation errors


## Normal Mode
Create a new repository and a dist directory. Inside of the dist directory create a new index.html file with the following html:

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" type="text/css" href="normalize.css">
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<a href="#" class="hamburger">
		<span></span>
	</a>
</body>
</html>
```

**Without modifying the HTML** replicate the following hamburger menu. Hint: you will need to use the `::before` and `::after` pseudo-elements.

![Normal Mode](/normal.png)
            
## Hard Mode
Using the hamburger menu that you just created, replicate the following behavior when the menu is clicked:

![Hard Mode](/hard.gif)

Hints: You will need to use a checkbox form element as well as the `:checked` CSS pseudo-class. You will also need to use the `~` CSS selector. [Read more about the ~ selector here](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_selectors).
           

## Notes
Hard mode is optional.

## Additional Resources

* [CSS pseudo-elements](https://github.com/TIY-Austin-Front-End-Engineering/Curriculum/tree/master/css-pseudo-elements)
* [General sibling selectors - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_selectors)
