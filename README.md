# crud-operation-generator
This package contains useful Artisan command.
# Installation

In your terminal:

> composer require zuezue/crud-generator

Add service provider to /config/app.php file:

> 'providers' => [
    Zuezue\Crud\Providers\CrudServiceProvider::class,
],

# Usage & Features

**make:crud**

This command tries to create a model, request class for validation ,a controller with crud operation and route automatically for a given name:

php artisan make:crud [name]
