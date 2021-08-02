# A docker-compose.yml file for WordPress, MySql and phpMyAdmin

Get up and running in a breeze without the hassle of installing and configuring PHP, Wordpress, MySql and phpMyAdmin.

## Usage

* Install docker from [https://www.docker.com/](https://www.docker.com/)
* Clone this repo
* Run `docker-compose up`

## Themes & plugins development

This is a really simple environment for themes & plugins development.

* Your WordPress installation will be available at `http://localhost:8000`
* The `wp-content` folder you'll find in this repo will be shared with the WordPress installation, put your code there.
* MySql data will persist between docker compose execution and will be accessibile via phpMyAdmin at `http://localhost:8080/`
