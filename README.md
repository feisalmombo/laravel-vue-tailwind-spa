This is Laravel 8, VueJS 3, Tailwind 3 SPA (Single Page Application) CRUD example for intermediate & advanced user. If you are a begineer, I recommend you to spend some time figuring out basic concept of Laravel & VueJS.


This sample "project" module demonstrating a complete CRUD operation. Below are the operations included in this repository:

* Listing all Projects
* Create a Project
* Edit a Project
* Delete a Project
* Alert before Deleting any Project
* Form Validation
* Loading Indicator

This project implements Laravel Requests, API Resource, Factory & Seeder to perform backend operations. The controller uses services for various actions to make code neat & clean.

This project is written with the composition API and script setup syntax to make your code clean. Also, it loads the route components dynamically using VueRouter. It uses VueX Store to perform API operations. Vutal also offers following basic components:

* Base Input
* Base Textarea
* Base Button
* Dropdown Menu
* Dropdown Item
* Base Card

```
composer install
php artisan migrate // Make sure you update database details in .env
npm install
npm run dev
```

