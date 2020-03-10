PHP POS Print (Local Server)
A php application for printing POS receipts

Installation
To clone and run this repository you'll need git, php & composer.

From your command line:

# Clone this repository
git clone https://github.com/geeksourcecodes/PHP-POS-Print-Server

# Go into the repository
cd PHP POS Print Server

# Install dependencies
composer install

# Start server from command line
php server.php

# Start app for settings
php -S localhost:8000 -t app/
Next time you can simply run php server.php in command line OR server.sh file to start the server.

This app runs at port 6441 ( ws://localhost:6441 ) and listen for the print jobs.

Get Windows Installer
Users having difficulty installing the PHP POS Print Server, can purchase standalone windows installer from link below

PHP POS Print Server (Windows Installer) http://elitepathsoftware.com/contact-us

Get 10% discount with offer code PHP POS Print Server (for limited time only).

It comes with logs feature. The server logs can be viewed or downloaded.

The license is not transfer-able, so please don't install it on test server.

Local printers
Server will try to use the local printers if no printer has been provided. You can access local app from your local web server url or just run php -S localhost:8000 -t app/ and access the app in browser http://localhost:8000

App Features

Main index page index.php to update your default printers
Printers page printers.php to list all your printers
Add Printer page add_printer.php to add new printer
The local settings will be saved in database/data.json file.

Screenshots



