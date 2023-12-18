

# Laravel with React + Inertia + tailwind 231218

Laravel 10 & Breeze with React.js, Inertia SSR, Tailwind CSS, PHPUnit

- [x] Laravel 10
- [x] Inertia SSR
- [x] React.js
- [x] Vite
- [x] Tailwind CSS

---

### Set Up 

Clone the repository 
```bash
git clone https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218.git && php artisan migrate && npm run dev
```

Enter the project directory
```bash
cd Laravel-with-React-Inertia-tailwind-231218
```

Create `.env` file from the example
```bash
cp .env.example .env
```

Generate the unique project identifier
```bash
php artisan key:generate
```

Install dependencies
```bash
composer install && npm install
```

Compile front-end area for live development
```bash
npm run dev
```

Compile the front-end area for production
```bash
npm run build
```

---


<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/1.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/2.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/3.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/4.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/5.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/6.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/7.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/8.png" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/documentation/img/9.png" width="400"></a></p>

---

```bash
composer require laravel/breeze --dev
```

```bash
php artisan breeze:install
```

```bash
 ┌ Which Breeze stack would you like to install? ───────────────┐
 │   ○ Blade with Alpine                                        │
 │   ○ Livewire (Volt Class API) with Alpine                    │
 │   ○ Livewire (Volt Functional API) with Alpine               │
 │ › ● React with Inertia                                       │
 │   ○ Vue with Inertia                                         │
 │   ○ API only                                                 │
 └──────────────────────────────────────────────────────────────┘
 ┌ Would you like any optional features? ───────────────────────┐
 │   ◻ Dark mode                                                │
 │ › ◻ Inertia SSR                                              │
 │   ◻ TypeScript (experimental)                                │
 └──────────────────────────────────────────────────────────────┘
 ┌ Which testing framework do you prefer? ──────────────────────┐
 │ › ● PHPUnit                                                  │
 │   ○ Pest                                                     │
 └──────────────────────────────────────────────────────────────┘
```

```bash
php artisan migrate && npm install && npm run dev
```

---

Laravel Breeze https://laravel.com/docs/10.x/starter-kits#laravel-breeze