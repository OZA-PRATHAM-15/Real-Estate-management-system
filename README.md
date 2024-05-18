# Real Estate Management System

This is a Real Estate Management System developed using PHP and MySQL. This system allows users to manage properties, clients, and transactions efficiently.

## Features

- Property Listings: Add, edit, delete, and view properties.
- Client Management: Manage client information and interactions.
- Transaction Records: Keep track of property transactions.
- User Authentication: Secure login and registration system.
- Dashboard: Overview of the real estate operations.

## Requirements

- WampServer
- Web Browser (Chrome, Firefox, etc.)

## Installation

### Step 1: Install WampServer

1. Download WampServer from [the official website](http://www.wampserver.com/en/).
2. Follow the installation instructions and install WampServer on your machine.

### Step 2: Clone the Repository

Clone the repository to your local machine

### Step 3: Copy Files to WampServer

1. Copy the cloned repository folder into the `www` directory of WampServer. By default, this directory is located at `C:\wamp64\www\`.

### Step 4: Import the SQL Database

1. Start WampServer and ensure that the server is running.
2. Open your web browser and navigate to `http://localhost/phpmyadmin`.
3. Log in to phpMyAdmin (the default username is `root` with no password).
4. Create a new database for the project. For example, name it `real_estate_db`.
5. Select the newly created database and click on the "Import" tab.
6. Click on "Choose File" and select the SQL file located in the `database` folder of the cloned repository.
7. Click "Go" to import the database.

### Step 5: Run the Project

1. Open your web browser.
2. Enter the following URL in the address bar: `http://localhost/real-estate-management`.
3. Press Enter.
4. You should see the login page of the Real Estate Management System.

## Screenshots
![Login Page](screenshots/login_page.png)
![Dashboard](screenshots/dashboard.png)
![Property Listing](screenshots/property_listing.png)


