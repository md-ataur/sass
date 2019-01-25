Install Anywhere (npm)
----------------------
If you use Node.js, you can also install Sass using npm by running

npm install -g sass


First install Sass using one of the options below, then run sass --version to be sure it installed correctly. If it did, this will include 1.16.1. You can also run sass --help for more information about the command-line interface.



You can also watch individual files or directories with the --watch flag. The watch flag tells Sass to watch your source files for changes, and re-compile CSS each time you save your Sass. 


sass --watch input.scss output.css


You can watch and output to directories by using folder paths as your input and output, and separating them with a colon. In this example:


sass --watch app/sass:public/stylesheets