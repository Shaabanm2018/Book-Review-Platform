<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Book Review Platform

The Book Review Platform is a Laravel-based web application that empowers book lovers to share their opinions, rate books, and discover new reads. It offers advanced search queries and sorting functionalities to enhance user experience and interaction within the book community.

## Features

- **User Registration and Authentication:** Secure sign-up and login processes for managing user profiles.
- **Advanced Search and Filtering:** Users can search for books by title and filter results by new entries, popularity, and ratings.
- **Review and Rating System:** Users can post reviews and rate books on a five-star scale.
- **Interactive Review Submission:** A dedicated page for adding detailed book reviews and ratings.
- **Admin Panel:** Administrators can manage book listings and user accounts, ensuring the platform remains a valuable resource for all users.

## Screenshots

### Home Page
![WhatsApp Image 2024-06-08 at 1 57 53 PM](https://github.com/Shaabanm2018/Book-Review-Platform/assets/76607364/60634a74-a8b7-4f9e-bf58-96d2bacd2839)


### Book Detail Page
![bookpage](https://github.com/Shaabanm2018/Book-Review-Platform/assets/76607364/549a544d-7f65-4942-9ca5-bfbe8c619f8f)


### Add Review Page
![addreview](https://github.com/Shaabanm2018/Book-Review-Platform/assets/76607364/c1393e8e-675f-4ddc-9b58-00b8c6434047)


![after reivew](https://github.com/Shaabanm2018/Book-Review-Platform/assets/76607364/69ef78f2-66a2-470b-8fe0-fb6d38171fe4)


### Search Functionality 
![search](https://github.com/Shaabanm2018/Book-Review-Platform/assets/76607364/b4ef5f89-277c-4398-9fd7-7c8552de2c1b)


## Requirements

- PHP >= 7.3
- Composer >= 2.4.2
- MySQL or any SQL-based database supported by Laravel

## Installation

1. **Clone the repository:**
   git clone https://github.com/Shaabanm2018/Book-Review-Platform.git
   cd Book-Review-Platform

## Setup Environment
- composer install
- cp .env.example .env

Access .env file and ensure the follwoing settings
- DB_CONNECTION=mysql
- DB_HOST=127.0.0.1
- DB_PORT=3306
- DB_DATABASE=laravel-10-book-review
- DB_USERNAME=root
- DB_PASSWORD=

- php artisan key:generate
- php artisan migrate
- php artisan db:seed

## Start the development server:
php artisan serve
Access the server at http://localhost:8000

## To access the database 
- Make sure docker-compose.yaml file exists
- Run docker-compose up -d
- Access database with http://localhost:8080/
- system MYSQL
- server mysql
- username root
- password root
  
## Usage
Browse Books: Use the advanced search options to find books by various criteria.
Add Reviews: Navigate to a book's detail page to add reviews and ratings.
Admin Features: Manage book entries and user accounts through the admin panel.

## Contributing
Contributions are welcome and greatly appreciated. To contribute:
Fork the project.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
