<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>
# Support Ticket Management System

![Logo](path/to/your/logo.png)

This Laravel-based project is designed to help junior developers practice building a support ticket management system, equipped with multiple user roles and dynamic features. This README provides details on system setup, usage, and additional resources.

## Project Overview

This system facilitates the handling of support tickets with three distinct user roles, each with specialized capabilities:

- **Admins:** Manage all system settings, assign tickets, and view detailed reports.
- **Team Members:** Address assigned tickets, view all tickets, and add internal comments not visible to the ticket creator.
- **Regular Users:** Submit and view their own tickets but cannot edit or delete them.

<h1 align="center" id="title">Laravel Support Ticket System</h1>

<p id="description">This Laravel-based project is designed to help need a support ticket management system equipped with multiple user roles and dynamic features. This README provides details on system setup usage and additional resources.</p>

<h2>🚀 Demo</h2>

[http://tickit.thekavak.com](http://tickit.thekavak.com)
<br><br>
 <h2>💻 Built with</h2>

Technologies used in the project:

*   Laravel 10
  
<br><br>
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Authentication: Implemented using Laravel session for streamlined registration and login processes. Users are assigned roles upon registration.
*   Ticket Management: Users can create tickets with titles html descriptions and drag-and-drop file attachments. Tickets can be assigned various priorities and statuses and categorized accordingly.
*   Admin Panel: Features a dashboard with ticket statistics and CRUD operations for managing Labels Categories Priorities and Users.
*   Interactivity: Ticket pages allow for user response and display a comprehensive activity log and update history.
*   Notifications:Automated email notifications alert Team Members about new or updated tickets.
<br><br>
<h2>🛠️ Installation Steps:</h2>
<br>
<p>1. Ensure you have the following installed:</p>

```
- PHP 8.0 or higher
- Composer
 - npm
```
<p><br>2. Download the source code</p>

<p><br>3. Install dependencies:</p>

```
composer install 
npm install
```

<p><br>4. Set up your environment file:</p>

```
cp .env.example .env
```

<p><br>5. Generate an application key:</p>

```
php artisan key:generate
```

<p><br>6. Run migrations:</p>

```
php artisan migrate
```

  
  
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
# Laravel-Support-Ticket-System
