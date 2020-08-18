STEP BY STEP INSTRUCTIONS

1. How to use SASS with NPM

a. create 2 seperate folders: 1 that will hold you html and your main css. This is called dist for me. Then create an scss folder that will hold all of your sass.

b. npm init in the terminal to initalize the package manager. Package.json

c. Install node-sass. This will create a node_modules files. npm install node-sass

d. in the node-modules file add a sass key value pair that can be ran afterwards that will take your scss and create a css file in the folder you want.

e. "sass": "node-sass -w scss/ -o dist/css --recursive"
what this script does is runs node-sass and the -w watches the scss folder, then the -o sets the output to dist/css folder.

f. In your html file make sure to link the stylesheet of MAIN.

2. Creating the header

a. first thing is to create the hamburger menu - I give the main div a class of menu-btn, then inside of it 3 divs with the clas btn-line to represent each line of the menu.

b. adding the nav - this will have to halves when the burger menu is clicked: menu-branding and menu-nav.

c. inside the menu-nav we add all the li tags inside a ul with an a tag that refer them to each html sheet. 

d. For the icons we use font - awesome. com.

e. After that we are going to create out main section. Inside this we will have an h1, h2, and our icons.

f. Jump into the main.css and we are going to start styling these things. all h's get margin: 0 and a lighter font-weight, nest inside the classes of lg-heading and sm-heading. We use the & parent selector to style the lg and sm headings and on the sm-heading we are adding some margin and padding as well as a rgba with the lighten function and some opacity.

g. transitions: all or color, 0.5s the time, ease out the effect