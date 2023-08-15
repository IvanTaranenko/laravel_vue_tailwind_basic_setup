# Laravel Vue Tailwind Basic Setup

This repository provides a basic setup for a Laravel project with Vue.js and Tailwind CSS. Follow the steps below to set up the project on your local machine.

## Getting Started

### Clone the Repository

To start, clone this repository to your local machine:


git clone https://github.com/IvanTaranenko/laravel_vue_tailwind_basic_setup.git
Install PHP Dependencies
Navigate to the project directory and install the PHP dependencies using Composer:

Copy code
```bash
composer install
```
Configure Environment
Create a .env file by copying the .env.example:


Copy code
```bash
cp .env.example .env
```

Generate the application key:
Copy code
```bash
php artisan key:generate
```
Run Laravel Development Server
Start the Laravel development server:


Copy code
```bash
php artisan serve
```
If necessary, you can refresh the database by running migrations with seed data:


Copy code
```bash
php artisan migrate:fresh --seed
```
Vue.js Setup
Install Node.js
Ensure you have Node.js installed. You can use the Node Version Manager (nvm) to install Node.js:


Copy code
```bash
nvm install node
```
Install Vue.js Dependencies
Install Vue.js dependencies using npm:


Copy code
```bash
npm install
```
Install the latest versions of Vue.js, Vue Router, and Vue Loader:


Copy code
```bash
npm install vue@next vue-router@next vue-loader@next
```
Install Vite
Install Vite and the Vue.js plugin for Vite:


Copy code
```bash
npm install @vitejs/plugin-vue --save-dev
```
Run the development server using Vite:


Copy code
```bash

npm run dev
```
Tailwind CSS Setup

Install Tailwind CSS
Install Tailwind CSS along with PostCSS and Autoprefixer:


Copy code
```bash

npm install -D tailwindcss postcss autoprefixer
```
Initialize the Tailwind CSS configuration:


Copy code
```bash

npx tailwindcss init -p
```
Laravel Breeze Installation
Install Laravel Breeze to set up authentication scaffolding:


Copy code
```bash

composer require laravel/breeze --dev
```
Install Vue.js-based Breeze:


Copy code
```bash

php artisan breeze:install vue
```
Install Vue.js-based Breeze with server-side rendering (SSR):


Copy code
```bash

php artisan breeze:install vue --ssr
```
Pinia Installation
Install the Pinia state management library for Vue.js:


Copy code
```bash
npm install pinia
```
Conclusion
Congratulations! You've successfully set up your Laravel project with Vue.js and Tailwind CSS. For more in-depth information and advanced usage, refer to the official documentation of Laravel, Vue.js, and Tailwind CSS.

Feel free to explore and customize this basic setup to fit your project's requirements. Happy coding!

