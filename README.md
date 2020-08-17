STEP BY STEP INSTRUCTIONS

1. How to use SASS with NPM

a. create 2 seperate folders: 1 that will hold you html and your main css. This is called dist for me. Then create an scss folder that will hold all of your sass.

b. npm init in the terminal to initalize the package manager. Package.json

c. Install node-sass. This will create a node_modules files. npm install node-sass

d. in the node-modules file add a sass key value pair that can be ran afterwards that will take your scss and create a css file in the folder you want.

e. "sass": "node-sass -w scss/ -o dist/css --recursive"
what this script does is runs node-sass and the -w watches the scss folder, then the -o sets the output to dist/css folder.

f. In your html file make sure to link the stylesheet of MAIN.