
# Template Websites

This repository has the template (setup and architecture) for HTML:5, CSS and Javascript projects


## Optimizations

The project configuration is based on 3 folders and a main HTML file.

- Assets: Folder to store resources such as images, icons or videos.
- Js: Folder to implement all the logic and functionality of the project through the Javascript language.
- Styles: Folder to style all the elements of the project, it consists of the following files: "main.css" where all the variables and generic styles at the level of the entire project will be found; "mobile.css" where all the styles will be found on small screens no larger than 576px and will be the main one due to the Mobile First strategy; "tablet.css" where the screen breaks greater than 576px but not greater than 996px will be found; Finally, "desktop.css" where the breaks of screens larger than 996px will be found.

According to the CSS methodology called SMACSS, generic styles at the tag level or reusable blocks should exist in separate CSS files and import them into the main file called "main.css".


## Authors

- [@AndresOrozcoDev](https://github.com/AndresOrozcoDev)

