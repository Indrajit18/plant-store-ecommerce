# plant-store-e-commerce
Plant Store E-commerce Website
Plant Store - Source code for an online plant store website built using PHP, MySQL, JavaScript, HTML and CSS. Features include customer login creation, interactive plant catalogue pages with pricing, descriptions and images, gardening tips content, sales analytics dashboards, and search and filter options on the home page with a green and white theme. The catalogue leverages MySQL and PHP for the backend with frontend functionality powered by JavaScript, HTML and CSS for a seamless customer experience.

Key details:

    Purpose - online plant store
    Tech stack: PHP, MySQL, JavaScript, HTML, CSS
    Functions: login, plant catalogue, tips content, analytics, search/filter, visually appealing plant images & theme
    Modularity - Catalog, storefront and tip components are modular for customization and extension.

This repository contains the complete source code for an e-commerce website selling plants and gardening supplies online.
Key Features

The website includes the following features:

    Browsing an interactive catalogue of houseplants, with pricing, images and descriptions
    Creating accounts and login functionality
    Managing customer profiles
    Processing online orders with integrated payments
    Order history and tracking status
    Gardening tips and inspirational content
    Sales and inventory analytics dashboards
    Robust search and filter options

Tech Stack

Built using:

    Frontend: HTML, CSS, JavaScript
    Backend: PHP, MySQL
    Hosting: Xampp

Documentation

Details on installation, configuration, component usage and customization - 
Download the Xampp software from - 
Installation

    Install XAMPP on your local machine
    Clone or download this repository into the "htdocs" folder of your XAMPP installation
    Open XAMPP and start the Apache and MySQL modules
    Open phpMyAdmin and create a new database (e.g. plant store)
    Import the SQL file from /database/plantstore.sql into the new database.

Configuration

The config file in /config/config.php contains variables for the database connection along with other general configuration options:

Copy code
define('DB_HOST', 'localhost');
define('DB_USER', 'your_username'); 
define('DB_PASS', 'your_password');
define('DB_NAME', 'plantstore');

Update the database username, password and other settings here according to your local setup.

There are also options to configure:

    Email sending
    Payment gateways
    Cache settings
    Error logging
    Other environment-specific options

///Only for Education purposes///
