# neptune

##INTRODUCTION

Neptune is a library that offers a modular building system for styling a react application based on scss and heavily inspired by atomic design and BEM.


##BEGRÜNDUNG

Many developers hate vanilla CSS. To be honest, I know no developer who doesn't struggle at least once in a while with CSS. Even it happens, that you have a perfect relation with CSS, a lot of tasks will be needed to complete by every new application, a big part of which is repetitive and not particularly creative or inspiring. That's why so many devs use CSS-Frameworks.
And there's nothing intrinsically wrong with CSS-Frameworks. The best tool is the tool that helps you. It's just... I don't particularly like them. I have three main issues with them:

I love to split tasks. I want my HTML to be HTML-ish, and write a bunch of rules inside an element simply hurts my heart. Yes, even with the best CSS architechture you can eventually have 2 (even more?) classes in a HTML element. But in my experience it just tends to be cleaner than a CSS-Framework-approach.
I find contra-intuitive to overwrite a css-Framework. To me this looks like a “I love you, you're perfect, now change” version for CSS. Why overwrite something when it's perfect? Why fight against your tool? And, if it's not perfect, why use don't use something better?
I don't find CSS-Frameworks particularly efficient. Yes, it may be efficient at a certain production level, after you learnt the syntax. And yet, I still think a good (s)css library will beat a CSS-Framework 10 / 10 times.
	a) You have new terminology to learn, or at least no class that you already probably use (or should use). 
	b) Since the whole system is basically a scss file, the developer has as much freedom and flexibility as one can desire
	c) Since the whole system is modular, every file has just one task. That makes the code tidy, “consequent” and easier to refactor.


##MISSION

Think less. Create more, 


##OBJECTIVES
Unite the flexibility of scss with the headache-free of a css framework and put it in the hands of developers


##PROJECTS

The project will have 2 main parts:
Library as npm package
A scss library to use in your project, with everything from fundational elements (a reset - … versión, colors, typography) up to different layouts, programmed in such a way you get a good design out of the box and at the same time the flexibility to easily customize this design according to your needs.
GUI Site
The second part will be a web with a GUI, where one can drag and drop elements into a canvas, and the site returns an the code. Good news: since it's scss, it's easy to refactor the downloaded files.
Documentation site
Aditionally, a documentation site for the developer is needed.


##DESCRIPTION
Library as npm package
Create a library { react components + scss files [ + images for the UI elements & layouts ]} that is modular, consistent, easy to scale and refactor, with a certain amount of UI components and layouts.
Simple and basic animations for certain elements that must be reactive (buttons, links and the alike)
Create @media for every file that needs it (pay atention to font size in relation with viewport)
Convert into a npm package

Documentation site

GUI Site
Write a program that returns scss files => abstract the logic from scss into js
Make a site that 
takes the action from the user and allows to create a wireframe in a GUI
traduces the elements from the GUI into values
stores the values in the be
traduces the values it into code with the program we wrote
stores the outcome from the program into a db
compiles every piece in the db into a file structure similar to the one from the library
offers the user to download the stored file
