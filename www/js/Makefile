build:  
	browserify -t babelify dispatcher.js menubar.js index.js -o bundle.js
ios:  
	browserify -t [ babelify --presets [ react ] ] dispatcher.js menubar.js index.js -o bundle.js
