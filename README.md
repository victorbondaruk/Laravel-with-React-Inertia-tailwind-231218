

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

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/1.png" alt="Home" caption="Home" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/2.png" alt="login" caption="login" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/3.png" alt="forgot-password" caption="forgot-password" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/4.png" alt="register" caption="register" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/5.png" alt="Home Auth" caption="Home Auth" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/6.png" alt="dashboard" caption="dashboard" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/7.png" alt="profile" caption="profile" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/8.png" alt="menu" caption="menu" width="400"></a></p>

<p align="center"><a href="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218" target="_blank"><img src="https://github.com/victorbondaruk/Laravel-with-React-Inertia-tailwind-231218/blob/main/documentation/images/9.png" alt="Log Out" caption="Log Out" width="400"></a></p>

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