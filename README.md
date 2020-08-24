<h1>About</h1>
Frontend workspace:<br/>
* download dependencies (css/js/components)<br/>
* watch changes (**f.**) on fly and livereload pages (**e.**)<br/>
* js:  concatenation all js files into one minified file (**min.**) and one not minified<br/>
* css: compilation sass to css with vendor prefixes (**min.**), concatenation all css files into one minified file (**min.** ) and one not minified<br/>
* images: image optimization , convertation png/jpg into webp <br/>

<br>
<h1>Quick start<sup>*</sup></h1>
1. `npm i` - install npm packages (required one time PER PROJECT)<br/>
2. `gulp` - run default task (development)<br/>
* step 0: must be installed [node] (https://nodejs.org/)  and gulp globally (npm install gulp -g)  - in case if it has not been installed yet - required one time PER MACHINE.<br/>
<h1>Plugins and custom css/js.</h1>
* js file ( **convertToWepP.js** ) replaces (**img** ) with (**picture** ) 
Custom css/js placed to main.css(main.min.css)/main.js(main.min.js). 
