##UI/UX Assessment Questions

_The correct questions are highlighted in bold_

1. At Andela, managing trainers is an important concern and one of the areas we would like to be able to collect data on would be Trainer professional development data. We would basically like to know how much professional development trainers are getting by giving them the ability to check-in courses they're attending, books they're reading, seminars they're speaking at, programs they're organising and exams they're taking. Create 3 screens that best incorporate the required functionality needed for this application. (Ambiguity is at a level where the fellows are able to still be creative. Assessment will be primarily on Information Architecture, Navigation, Understanding the User, Interaction Design and Copywriting).
2. Which of the following are software that can be used to create Wireframes (Select all that apply)
	- **Photoshop**
	- **Balsamiq**
	- Invision
	- MarvelApp
	- Sublime Text
3. Which of the following components would you use to group similar functionality within a page in your User Interface (Select all that apply)
	- **Accordions**
	- Sliders
	- Buttons
	- **Tabs**
	- Modal Boxes
4. Grid systems enable all of the following except
	- They increase productivity
	- **They give your layouts aesthetic value**
	- They are ideal for responsive layouts
	- They reduce the amount of code you need to write moving on to new projects
5. Which CSS snippet will give me this layout (Two overlapping boxes with a smaller box at the top right corner of the bigger box)
![CSS Task Diagram](/images/diagram_1.png)
	- Snippet 1
	```
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
	- **Snippet 2**
	```
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
	- Snippet 3
	```
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
6. What is an the advantage of using CSS pre-processors over regular CSS
	- Ability to put comments within your CSS
	- Selectors are `:not(element)` are not available in regular CSS
	- **Nesting of selectors within each other**
	- Ability to import external CSS within your CSS file
7. What are the things to consider most when making your application responsive? (Select all that apply)
	- **Improve performance**
	- Reduce important functionality
	- **Emphasise vertical scrolling**
	- Serve multiple versions of the same application
8. What is the best way to visualise the amount of time a user is available in day?
	- Histogram
	- **Pie Chart**
	- Line Chart
	- Stacked Area Chart
9. Which of the following is the best feedback mechanisms when a user is uploading an image on the page?
	- Using an Indeterminate loading bar
	- **Using a percent slider**
	- Showing loading text on the page
	- Disabling all the elements on the page
10. Which of the following button states correspond to the appropriate CSS state
	- `mouse over => :over `
	- `mouse out => :out`
	- `mouse down => :active`
	- `mouse over => :active`