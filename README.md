composer install

npm install

php artisan key:generate

go to \app\Providers and put this 2 lines of codes

use Illuminate\Support\Facades\Schema;

public function boot()
    {
        Schema::defaultStringLength(191);
    }

php artisan migrate

php artisan db:seed

npm run dev

npm run watch

php artisan serve

============================================

admin@gmail.com

11111111

----------------------------------------------

author@gmail.com

11111111