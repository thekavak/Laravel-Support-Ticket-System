
<h1 align="center" id="title">Laravel Support Ticket System</h1>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/main.png)

<h1 align="center" id="title">
  <a href="https://thekavak.gumroad.com/l/laravel-ticket-system" target="_blank">
    📥 Download Source Code for Free!
  </a>
</h1>

<h2>🔐 Login</h2>

![Login](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/login.png)
<h2>📊 Dashboard</h2>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/home.png)
<h2>👥 Users Page</h2>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/user.png)
<h2>📈 Status Page</h2>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/status.png)
<h2>📝 Ticket List</h2>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/list.png)
<h2>🔍 Ticket Detail</h2>

![Logo](https://raw.githubusercontent.com/thekavak/Laravel-Support-Ticket-System/main/assets/detail.png)

<h1 align="center" id="title">
  <a href="https://thekavak.gumroad.com/l/laravel-ticket-system" target="_blank">
    📥 Download Source Code for Free!
  </a>
</h1>
<p id="description">This Laravel-based project is designed to help need a support ticket management system equipped with multiple user roles and dynamic features. This README provides details on system setup usage and additional resources.</p>

## Project Overview

This system facilitates the handling of support tickets with three distinct user roles, each with specialized capabilities:

- **Admins:** Manage all system settings, assign tickets, and view detailed reports.
- **Team Members:** Answer assigned tickets, reassign, view all tickets, and add internal comments that are not visible to the person who created the ticket.
- **Regular Users:** They can submit and view their own tickets and add file and html description but cannot edit or delete them.

<h2>🚀 Demo</h2>

[http://tickit.thekavak.com](http://tickit.thekavak.com)
<br><br>

<h3>Demo Users</h3>
To explore the system, use the following demo credentials:

Admin Login: Email: admin@tickit.com | Password: password
Regular User Login: Email: user@tickit.com | Password: password

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

<h1 align="center" id="title">
  <a href="https://thekavak.gumroad.com/l/laravel-ticket-system" target="_blank">
    📥 Download Source Code for Free!
  </a>
</h1>
  
## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
# Laravel-Support-Ticket-System
