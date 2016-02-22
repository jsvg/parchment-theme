### Parchment Theme for Ghost

Responsive blog theme made for specifically for the [Ghost platform](https://ghost.org). Built with minimalistic design principles that shift focus to narrative and content. Theme was custom-built for a single purpose, therefore third party use requires further development. Consider this a starting point.

Notable features:
* Custom navigation links
* SCSS deconstructed stylesheets
* [Animsition](http://blivesta.github.io/animsition) smooth page transfers

#### Screenshots

__Home Page__

![Home Page](https://raw.githubusercontent.com/jsvg/parchment-theme/master/Screenshot_Cover.png)

__Post__

![Post](https://raw.githubusercontent.com/jsvg/parchment-theme/master/Screenshot_Post.png)

#### Applying to Ghost Digital Ocean Droplet
#. cd into theme dir (cd /var/www/ghost/content/themes)
#. rm -rf parchment/
#. git clone https://github.com/jsvg/parchment-theme
#. mv parchment-theme/ parchment/
#. chown -R ghost:ghost parchment
#. service ghost restart

#### License
[![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)](http://www.wtfpl.net/)