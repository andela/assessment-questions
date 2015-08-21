##UI/UX Assessment Questions
**Summary**

This document contains questions that test a fellows knowledge of the following concepts

- Wireframing
- Color Theory
- UI components
- UI behaviour
- Layouts

_The correct answers are highlighted in bold_

1. Which of the following is a software that can be used to create Mockups
	- Sublime Text
	- **Balsamiq**
	- Invision
	- MarvelApp
2. Which of the following components would you use to group similar functionality within a page in your User Interface
	- Sliders
	- Buttons
	- **Tabs**
	- Modal Boxes
3. Which of the following is not a benefit of using Grid systems
	- They increase productivity
	- **They give your layouts aesthetic value**
	- They are ideal for responsive layouts
	- They reduce the amount of code you need to write moving on to new projects
4. Which CSS snippet will give me this layout (Two overlapping boxes with a smaller box at the top right corner of the bigger box)
_**Link to image**_

	Snippet 1
	```css
	big-box {
    	position: relative;
    	max-width: 150px;
    	height: -150px;
	}
	small-box {
		position: fixed;
		margin-top: -25px;
    	margin-right: -25px;
	}
	```

	**Snippet 2**
	```css
	big-box {
    	position: relative;
    	width: 150px;
    	height: 150px;
	}
	small-box {
		position: absolute;
		top: -25px;
    	right: -25px;
	}
	```

	Snippet 3
	```css
	big-box {
    	position: absolute;
    	width: 150px;
    	height: 150px;
	}
	small-box {
		position: relative;
		margin-top: -25px;
    margin-right: -25px;
	}
	```
5. What is an the advantage of using CSS pre-processors over regular CSS
	- Ability to put comments within your CSS
	- Selectors like `:not(element)` are not available in regular CSS
	- **Nesting of selectors within each other**
	- Ability to import external CSS within your CSS file
6. What is an important consideration when making your application responsive?
	- Remove primary functionality
	- **Emphasise vertical scrolling**
	- Serve multiple versions of the same application
	- Remove images whenever possible
7. What is the best way to visualise the amount of time a user is available in day?
	- Histogram
	- **Pie Chart**
	- Line Chart
	- Stacked Area Chart
8. Which of the following is the best feedback mechanism when a user is uploading an image on the page?
	- Using an Indeterminate loading bar
	- **Using a percent slider**
	- Showing loading text on the page
	- Disabling all the elements on the page
9. Which of the following button states correspond to the appropriate CSS state
	- `mouse over => :over `
	- `mouse out => :out`
	- `mouse down => :active`
	- `mouse over => :active`
