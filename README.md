## Laravel-Saas Demo
- This is saas base laravel demo project.
- Reference: ```https://github.com/LaravelDaily/Laravel-SaaS-Subscriptions-Demo```.
- Package Reference: ```https://github.com/lucasdotvin/laravel-soulbscription```.
## Installation
- First you have to clone this project

```
git clone https://github.com/NihirRootways/laravel-saas.git
```

- Than you have to update the composer dependencies using ```composer update``` command.
- After this you have to create ```.env``` file using ```cp .env.example .env``` command.
- Than you have to create the ```APP_KEY``` using ```php artisan key:generate```.
- You have to configure the database.
- Enter the database name and run following command

```
php artisan migrate:fresh --seed
```

## User login information

- Email:     ```admin@admin.com``` 
- Password:  ```password```
