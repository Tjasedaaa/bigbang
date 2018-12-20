BIGBANG WORDPRESS STARTER THEME
=================================


This is a worpdress starter theme based on Underscore theme. It includes npm packages as well as Gulpfile, folder stystem and webpack configuration file. You can customize this theme to your liking. Because it is a starter theme you do not need to create child theme.

# Instalation

- Download zip file or clone this repo to local directory
- In the directory use cmd to install npm packages:
```sh
$ npm install
```
- open **settings.js** file and change settings according to your needs
- in cmd run:
```sh
$ gulp watch
```

Gulp should start and watch for any changes to assets/sass folder, assets/js/dev folder, assets/images/originals folder and any php file in theme directory.

You can also change the name of your theme. Make sure you change the name everywhere in theme directory and don't forget to change theme settings in assets/sass/style.scss (in the top comment).
