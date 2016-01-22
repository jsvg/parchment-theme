### Parchment Theme

#### License
MIT

Updating Ghost Droplet
1. cd into theme dir (cd /var/www/ghost/content/themes)
2. rm -rf parchment/
2. git clone https://github.com/jsvg/parchment-theme
3. mv parchment-theme/ parchment/
4. chown -R ghost:ghost parchment
5. service ghost restart