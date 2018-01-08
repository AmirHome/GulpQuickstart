# GulpQuickstart
Gulp js for CSS HTML JavaScript minify task and ftp upload task with authorization

### init Nodejs
		
		... from within our project folder
		$ npm init (Optional)
		$ npm install gulp -g

		* install gulp plugin
		$ npm install in the gulpfile.js

		Remove node_modules
		$ npm install rimraf -g $ rimraf node_modules

		* install plugins
		$ npm install gulp gulp-useref gulp-if gulp-uglify gulp-cssnano del gulp-livereload gulp-clean gulp-replace gulp-htmlmin gulp-git gulp-util vinyl-ftp yargs fs gulp-run-sequence --save-dev

### Help Commands

	$ gulp help

>		ftp-deploy            Upload modified git with ftp
>		                     Parameters:
>		                     -d Domain -u username -p password [-f Full Transfer]
>
>		mini-deploy           Minify html, css, js and upload modified git with ftp
>		                     Parameters:
>		                     -d Domain -u username -p password [-f Full Transfer]
>
>		create-version        Create tag for this version git
