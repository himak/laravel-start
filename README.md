# Laravel Start App

This is Laravel simple app with Bootstrap CSS.

### Install App

Defautl database is SQLite

	database/database.sqlite

Run this command

	php artisan migrate
	php artisan kye:generate

### After deploy on hosting

Set app to production mode and turn off debug mode in **.env**

	APP_ENV=production
	APP_DEBUG=false