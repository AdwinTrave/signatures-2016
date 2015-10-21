# signatures-2016
## Setup
This repository contains all the files for a Concrete 5 theme.

### XAMPP
If you want to develop on you local machine start by installing [XAMPP](https://www.apachefriends.org/) or equivalent.

### Concrete 5
1 - Download at: https://www.concrete5.org/get-started

2 - Follow installation instructions at: https://www.concrete5.org/documentation/developers/5.7/installation/installation/

2.1 - For database you want to use MySql Admin that should be provided with XAMPP, if not download [phpMyAdmin](http://www.phpmyadmin.net/)

You only need to put it into a directory on your localhost and then log in with you mysql credentials that you have created when installing XAMPP.

### Github
After you have Concrete 5 running on your localhost get [GitHub management tool](https://desktop.github.com/)

Clone this repository to your Concrete 5 installation and in the following directory `application/themes/`

It should create a signatures-2016 directory and you should be able to enable the theme via administration in Concrete 5.

## RIT Staging
About once a week changes in this repository will be uploaded to RIT stagin so that they are easily accessible to everyon. The development site is located at: http://www-staging.rit.edu/sg/signature/

## Moving into production
Once a theme is approved it will be transfered into the production server from staging.

## What is what?
The theme uses [Bootstrap](http://getbootstrap.com/) as its base. Hence all that Bootstrap has we can use as well.

### CSS
To modify default variables like colors, fonts, etc. you need to adjust the `css/presets/defaults.less` variables.

For more in-depth editing explore `css/build/`, but make sure that you use variables from `css/presets/defaults.less` or create new ones there, so that future generations have easier time editing it.

### Templates
First of all, DO NOT edit any of the PHP unless you have read Concrete 5 documentation and know what you are doing.

Header and footer templates are editable under `elements/`
Other elements are available in the root.

