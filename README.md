<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
  <!-- Build Status -->
  <a href="https://travis-ci.com/USERNAME/laravel-tailwindcss-Blog">
    <img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status">
  </a>

  <!-- Total Downloads (project-specific, optional) -->
  <a href="#">
    <img src="https://img.shields.io/badge/downloads-–-blue" alt="Total Downloads">
  </a>

  <!-- Laravel Version (fixed for your project) -->
  <a href="https://laravel.com/">
    <img src="https://img.shields.io/badge/Laravel-9.x-red" alt="Laravel Version">
  </a>

  <!-- License -->
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="License">
  </a>
</p>

 # Laravel TailwindCSS Blog

A simple and clean Blog application built with **Laravel 9** and **Tailwind CSS 3**, featuring full CRUD functionality and trash management.

## Features

- Create, Read, Update, Delete (CRUD) blog posts
- Soft Delete: articles can be trashed and restored
- Force Delete: permanently remove articles
- Responsive design using Tailwind CSS
- Blade templating engine for views
- Clean and organized code structure

## Tech Stack

- Laravel 9 (PHP Framework)
- Tailwind CSS 3
- MySQL
- Blade templates
- Composer for dependencies
- Git for version control

## Installation

1. Clone the repository:
```bash
git clone https://github.com/USERNAME/laravel-tailwindcss-Blog.git
```
2. Install dependencies:
   
``bash
composer install
npm install && npm run dev
``
4. Set up environment variables:
<br>
1-Copy .env.example to .env
<br>
2-Configure your database
<br>
3-Run migrations:
<br>
``bash
php artisan migrate
``
<br>
4.Serve the application:
``bash
php artisan serve
``
### Usage:
**-Create** new blog posts

**-Edit** existing posts

**-Trash** posts instead of immediate deletion

**-Restore** trashed posts from the trash

**-Permanently delete** posts using Force Delete

