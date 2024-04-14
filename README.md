<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

Simple ToDo List App

Description

This Simple ToDo List application is a straightforward, yet powerful, tool built using Laravel. It's designed to help users manage their daily tasks efficiently, allowing for task additions, updates and deletions all within a user-friendly interface.

Features

Add Tasks: Easily add new tasks to your list.
Edit Tasks: Update details of existing tasks as your needs change.
Delete Tasks: Remove completed or unnecessary tasks.

Prerequisites
PHP 7.3 or higher
MySQL or another compatible database server
Composer for managing PHP packages
Node.js and NPM (optional for asset compilation)
Setup Instructions
Clone the Repository
bash
Copy code
git clone https://github.com/Spyros34/Simple-ToDo-List-.git
cd Simple-ToDo-List
Install Dependencies
bash
Copy code
composer install
npm install && npm run dev  # Optional: if you are handling frontend assets
Environment Configuration
Create an .env file from the example provided and adjust it for your environment:
bash
Copy code
cp .env.example .env
Generate Application Key
bash
Copy code
php artisan key:generate
Database Migration
Set up your database schema:
bash
Copy code
php artisan migrate
Serve the Application
Start your local development server:
bash
Copy code
php artisan serve
The application will be available at http://localhost:8000.
Usage

Begin managing your tasks by visiting http://localhost:8000. The interface is intuitive, guiding you through adding, editing, and deleting tasks.

Contact

Spyros - GitHub Profile

Project Link: https://github.com/Spyros34/Simple-ToDo-List-.git
