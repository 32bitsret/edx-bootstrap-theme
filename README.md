# edx-bootstrap-theme
edx-bootstrap-theme for open edX dogwood release (comprehensive theming)

> Open edX responsive theme using [Bootstrap](http://getbootstrap.com/).

![Screenshot](https://raw.githubusercontent.com/dadasoz/edx-bootstrap-theme/docs/images/1.png)
![Screenshot](https://raw.githubusercontent.com/IONISx/edx-bootstrap-theme/docs/images/2.png)
![Screenshot](https://raw.githubusercontent.com/IONISx/edx-bootstrap-theme/docs/images/3.png)
![Screenshot](https://raw.githubusercontent.com/IONISx/edx-bootstrap-theme/docs/images/4.png)

## About this Open edX theme

It is based on [Bootstrap](http://getbootstrap.com/), it uses bootstrap's Sass library – which is used by Open edX).

## How to use this theme (devstack)

First, open your '/edx/app/edxapp/edx-platform/themes' directory and clone this repo in as edx-bootstrap-theme. 

Next, open your 'lms.env.json' file and edit 'COMPREHENSIVE_THEME_DIR' to '/edx/app/edxapp/edx-platform/themes/edx-bootstrap-theme'

Save this file, and run 'paver updaate_assets lms' then 'paver lms'.
