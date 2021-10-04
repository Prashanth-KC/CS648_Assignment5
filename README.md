**_There is only one webpage index.html but styled using SASS and with the help of gulp the scss file is complied to css file_**

# dist
## Distribution folder conatining styles.css, index.html and other images used in the webpage.
> Index.html-main webpage

# src
## _Source folder containing styles.scss and all other partials.scss files_
* styles.scss imports all the partials
* _base.scss is the SASS script for body
* _content.scss is the SASS script for content of the html
* _footer.scss is the SASS script for footer of the html
* _header.scss is the SASS script for header of the html
* _mixins.scss is the SASS script for all mixins functiosn with bakground images, etc.
* _navbar.scss is the SASS script for nav tag
* _variables.scss is the SASS script for all the variables used in all the scss files


# gulp.js
>Contains the gulp task runner to compile scss to css.