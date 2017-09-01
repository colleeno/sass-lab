# Sass Lab

I chose to learn Sass for this lab, otherwise known as 'Syntactically Awesome Stylesheets'. While Sass files can be written without brackets and semi-colons, I used the .scss option, often referred to as 'Sassy Stylesheets' as it more closely resembles the css syntax.

I've seen some of the syntax before, and more recently have seen it as a required skill for development jobs. Comfortable with CSS, it seemed a skill I could learn in this timeframe.

Sass adds features to CSS that don't currently exist. For example you can store chunks of code in variables to be referenced in your project. You can then update a variable once and apply the changes everywhere. You can also separate out partials, and create 'dryer' code. Everything done in Sass can be accomplished in CSS, it is after all converted to a CSS file in the end, just not as cleanly. It is ideal for large projects to be able to repeat and update code more easily.

To use:
* run $gem install sass (if you have ruby installed you already have this)
* set up your html file as usual
* create a file for your sass, 'main.scss'
* $sass --watch main.scss:main.css - this will add a .css file and listen and update your changes to .scss

One alternative is LESS.

Created by Hampton Catlin to add functionality that does not yet exist in CSS. Primary Devs: Nathan Weizenbaum & Chris Eppstein.

I enjoyed learning Sass and understand it's massive appeal. One feature I was disappointed to find, is the inability to set variables based off user interactions. I initially wanted to create a color picker swatch palette, until I realized scss has no way to read the html inputs.

I would recommend the Code School Sass tutorial to anyone interested. It is linked in my project.   
