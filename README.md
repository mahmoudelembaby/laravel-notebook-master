# Laravel Notebook
Notebook is a interactive note taking application created to organize your notes on the web. I made this with Laravel 7.

## What are the functionalities of Notebook 
- Users can register themselves an account and starting taking notes.
- BASIC CRUD for ```Notebooks``` and ```Notes```
- A inline WYSIWIG Editor to edit your notes content seamlessly.

### Steps for Installation
```
git clone https://github.com/mahmoudelembaby/Laravel-Notebook.git laravel-notebook
cd laravel-notebook
composer install
cp .env.example .env
php artisan migrate --seed
php artisan key:generate
php artisan storage:link
php artisan serve
```