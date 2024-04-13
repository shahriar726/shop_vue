# shop_vue
1.E-commerce application built with Laravel, Vue.js, Tailwind.css and Inertia.js with Stripe Payment

2.installation

3.Make sure you have environment setup properly. You will need MySQL, PHP8.1, Node.js and composer.

4.Install Laravel Website + API

5.Download the project (or clone using GIT)

6.Copy .env.example into .env and configure database credentials

7.Navigate to the project's root directory using terminal

8.Run composer install

9.Set the encryption key by executing php artisan key:generate

10.Run migrations php artisan migrate --seed

11.Run data seeder to test  php artisan db:seed AdminSeeder and and other db seeder files you can find under database/seeders

12.Start local server by executing php artisan serve

13.Open new terminal and navigate to the project root directory Run npm install

14.Run npm run dev to start vite server for Laravel frontend

For Stripe Api key, please go to .env file and replace with your api key for this variable STRIPE_KEY="REPLACE WITH YOUR STRIP API KEY HERE"


