# Notes-App
## Experiment 9 LARAVEL FRAMEWORK.

## Installation Steps
1. Install [XAMPP](https://www.apachefriends.org/index.html).

2. Intall [Composer](https://getcomposer.org/). Put correct path for PHP during installation. The file _php.exe_ is in _php_ directory in the XAMPP installation folder.

3. Install [Node.js](https://nodejs.org/en/) along with npm.

4. Create a database "notes" from PhpMyAdmin. Set MySQL database credentials in _.env_ file. Make database model for notes using phpmyadmin:

5. Add keys to .env file:
```
php artisan key:generate
```
6. Add all views and layouts (resources/views), controller functions (app/Http/Controllers/NotesController.php), model details (app/Note.php) and migrations (database/migrations/create_notes_table.php). Run the follwing command:
```
php artisan migrate
```
7. We have already installed laravel collectives. Make changes to _config/app.php_ as shown [here](https://laravelcollective.com/docs/5.6/html).

8. Make sure that the Apache server and MySQL are running. The project site will be visible at  http://127.0.0.1:8000. This will be your local server, website won't be accessible via web.
```
php artisan run server
```
