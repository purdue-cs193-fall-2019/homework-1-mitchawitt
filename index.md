# Mitchell Witt's First CS193 Homework

<body style="margin:  0">
	<canvas id="canvas" width="0" height="0"></canvas>
	<style>
		body{
			background-color: black;
		}

		input{
			padding: 5px 10px;
			margin-left: 20px;
		  -webkit-appearance: none;  /* Override default CSS styles */
		  appearance: none;
		  height: 25px; /* Specified height */
		  background: #d3d3d3; /* Grey background */
		  outline: none; /* Remove outline */
		  opacity: 0.7; /* Set transparency (for mouse-over effects on hover) */
		  -webkit-transition: .2s; /* 0.2 seconds transition on hover */
		  transition: opacity .2s;
		}
		/* Mouse-over effects */
		input:hover {
		  opacity: 1;
		}

		input::-moz-range-thumb {
		  width: 25px; /* Set a specific slider handle width */
		  height: 25px; /* Slider handle height */
		  background: #4CAF50; /* Green background */
		  cursor: pointer; /* Cursor on hover */
		}

		input::-webkit-slider-thumb {
		  -webkit-appearance: none;
		  appearance: none;
		  width: 25px;
		  height: 25px;
		  background: #4CAF50;
		  cursor: pointer;
		}

		font{
			font-family: arial;
			color: white;
			size: 5;
			margin-left: 20px;
		}

	</style>
	<div style = "background-color: gray; width: 200px; height: 740px; position: absolute; top:10px; right:10px;">

		<p><font>Length (pixels): <span id="lengthValue"></span></font></p>
		<input type="range" min = "1" max = "300" value = "150" id = "lengthSlider" font="white;"></input>

		<p><font>Number of partitions: <span id="partitionValue"></span></font></p>
		<input type="range" min = "1" max = "6" value = "3" id = "partitionSlider"></input>

		<p><font>Number of branches: <span id="branchValue"></span></font></p>
		<input type="range" min = "1" max = "6" value = "3" id = "branchSlider"></input>

    <p><font>Radial Scaling #1: <span id="radialValue1"></span></font></p>
		<input type="range" min = "0" max = "20" value = "5" id = "radialSlider1"></input>

		<p><font>Radial Scaling #2: <span id="radialValue2"></span></font></p>
		<input type="range" min = "0" max = "20" value = "5" id = "radialSlider2"></input>

		<p><font>Radial Scaling #3: <span id="radialValue3"></span></font></p>
		<input type="range" min = "0" max = "20" value = "5" id = "radialSlider3"></input>

		<p><font>Radial Scaling #4: <span id="radialValue4"></span></font></p>
		<input type="range" min = "0" max = "20" id = "radialSlider4" disabled></input>

		<p><font>Radial Scaling #5: <span id="radialValue5"></span></font></p>
		<input type="range" min = "0" max = "20" id = "radialSlider5" disabled></input>

		<p><font>Radial Scaling #6: <span id="radialValue6"></span></font></p>
		<input type="range" min = "0" max = "20" id = "radialSlider6" disabled></input>

	</div>
	<script src="fractalGen.js"></script>
</body>

## Favorite things about CS193
- Making me get a GitHub Pro account for free
- Class playlist is okay
- Run by undergrads so it's pretty chill

### Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/kalutes/CS193_Fall18_Lab1/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

#### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Heading1
## Heading2
### Heading3

- bulleted
- list

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

#### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kalutes/CS193_Fall18_Lab1/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

#### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
