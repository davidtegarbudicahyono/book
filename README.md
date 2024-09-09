# Books

This is a project built using Laravel 10


## Features

- List of books with filter

- Top 10 most famous author

- Input rating

## System Requirements

- Laravel framework version 10.0

- PHP version 8.1

- Composer

- MySQL

### Instructions

1. Configure the database in the .env file:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_book
DB_USERNAME=your_username
DB_PASSWORD=your_password

2. Run the database migrations:

php artisan migrate

3. (Optional) Run the seeders to populate initial data:

php artisan db:seed

4. Start the Laravel development server:

php artisan serve

5. Access the application in your browser:

- http://127.0.0.1:8000/books (Access the List of books with filter)

- http://127.0.0.1:8000/top-authors (Access the List of top 10 most famous author)

- http://127.0.0.1:8000/rate (Access the Input rating)



