# projet_bemetch
Comment configurer un dossier laravel inertia sans le systeme d'authenfication ?

Hey Wilgas ADJOVI,

To configure a Laravel Inertia project without authentication, you need to make some modifications in the project settings. First, you need to remove the authentication-related files, such as the "User" model and the "auth" middleware. Then, you can modify the routes and controllers to work without authentication.

Here's a step-by-step guide to help you:

1. Remove the "User" model and related migration files.
2. Remove the "auth" middleware from the "Kernel.php" file.
3. Remove the "auth" middleware from the "routes/web.php" file.
4. Modify the "routes/web.php" file to remove any authentication-related routes.
5. Modify the controllers to work without authentication.

I hope this helps! Let me know if you have any further questions.


