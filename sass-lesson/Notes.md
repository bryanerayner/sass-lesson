# Steps for installing Ruby on Windows

Download ruby installer, http://rubyinstaller.org/downloads/

## Installing SASS

	$ gem install sass

## Using SASS

### Configure SCSS conversion watching

	$ sass --watch scss:css

### Configure SCSS conversion watching, minifying files

	$ sass --watch scss:css --style compressed

### Generate source file for use with Chrome Dev Tools

First, SASS must be at the pre release version, 3.3.0. Install using this code:

	$ gem install

Single file: 
	
	$ sass --watch scss:css --sourcemap sass/styles.scss:styles.css

	
	
Funny broswer things

-Instead of last child, put the styles on everything and remove stuff from the first child.