# laravel-related-commands

## create a new project

### install laravel globally
`composer global require laravel/installer`
### create a laravel project
`laravel new project-name`


### seed the Database with created Factories and seeder
`php artisan db:seed`

run the migrations and also seed the data
`php artisan migrate --seed`

run the migration by dropping all previous database (roleback) and also run seed
`php artisan migrate:refresh  --seed`
