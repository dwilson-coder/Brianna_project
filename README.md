
#Portfolio Project

This is a redesign of a portfolio project taught by Simo Edwin.
I wanted to demonstrate how adding Sass, could add scalability to even simple HTML projects.

![Desktop version](/img/desktop_screenshot.jpg)
![Mobile version](/img/mobile-screenshot.jpg)

## Acknowledgements

 - [Edwin's Creative HTML & CSS3 Course](https://www.udemy.com/course/the-creative-html5-css3-course-build-awesome-websites/)
 - [Working with Npm](https://docs.npmjs.com/)
 - [Working with Sass](https://sass-lang.com/guide)
 - [Images of model - pngwing.com](https://www.pngwing.com/en/free-png-bptgh)
 - [Other images - pexels.com](https://www.pexels.com/)

## Authors

- [@dwilson-coder](https://github.com/dwilson-coder)


## Command Line Prompts

To initialize a Sass project

`npm init`

To install the node file directory

`npm install node-sass`

or to add dependencies to your .json file

`npm install node-sass --dev-save`


The .json file has the following code:

`"Scripts": {
    "compile:sass": "node-sass sass/main.scss css/styles.css -w";
}`

So, when you run the `npm run compile:sass command`, you can watch for changes in the code and automatically a single `style.css` file from your Sass code.

To run 'Live-Server', simply type the following command

`live-server`
