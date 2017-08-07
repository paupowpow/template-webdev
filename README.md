# template-webdev
Quick starting my web dev projects. Includes:

* local webserver
* sass to css
* automatic browser refresh
* tasks for optimizing assets for productions

I followed this neat [tutorial](https://css-tricks.com/gulp-for-beginners/).

## requirements
1. `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` to get the Homebrew package manager for macOS
2. `brew install npm` to install npm, the Node.js package manager

## run it
1. `git clone https://github.com/paupowpow/template-webdev.git` to download the repository
2. `cd template-webdev` to go into the folder
3. `sudo npm install gulp -g` to install gulp globally OR `npm install gulp` to install gulp inside
4. `gulp` to compile sass to css, start local machine and watch on changes to html, js, css files

## build
`gulp build`


