# Sass Lab

I chose to learn Sass for this lab, otherwise known as 'Syntactically Awesome Stylesheets'. While Sass files can be written without brackets and semi-colons, I used the .scss option, often referred to as 'Sassy Stylesheets' as it more closely resembles the css syntax.

I've seen some of the syntax before, and more recently have seen it as a required skill for development jobs. Comfortable with CSS, it seemed a skill I could learn in this timeframe.

Sass adds features to CSS that don't currently exist. For example you can store chunks of code in variables to be referenced in your project. You can then update a variable once and apply the changes everywhere. You can also separate out partials, and create 'dryer' code. Everything done in Sass can be accomplished in CSS, it is after all converted to a CSS file in the end, just not as cleanly. It is ideal for large projects to be able to repeat and update code more easily.

To use
* run $gem install sass (if you have ruby installed you already have this)
* set up your html file as usual
* create a file for your sass, 'main.scss'
* $sass --watch main.scss:main.css This will add a .css file and listen and update your changes to .scss
* link your css file in your html as usual

One alternative is LESS.

Created by Hampton Catlin to add functionality that does not yet exist in CSS. Primary Devs: Nathan Weizenbaum & Chris Eppstein.

I enjoyed learning Sass and understand it's massive appeal. One feature I was disappointed to find, is the inability to set variables based off user interactions. I initially wanted to create a color picker swatch palette, until I realized scss has no way to read the html inputs.

I would recommend the Code School Sass tutorial to anyone interested. It is linked in my project.

Relevant questions might be
* How do you set a variable?
* When could a mixin be useful?
* How might Sass overcomplicate styling?

To test out, clone down this repo. You'll want to set the project up to watch for changes to the scss, so type $sass --watch main.scss:main.css.
Open the project in atom and the index.html file in your browser. Trying changing the $color variable value and see how easy it is to update your entire project with a variable.  
Look through the .scss and .css files to see how the .scss is translated to .css.

NOTE - this is an EXTREME example, and is not a good way to write your styles!
