# Flavordex API Server

This is the backend server that the Flavordex app uses to sync journal data.

   * [Official Website](http://flavordex.ultramegasoft.com/)
   * [Flavordex for Android on GitHub](https://github.com/ultramega/flavordex)

## Requirements

   * PHP 5.5
   * MySQL 5.6
   * PHP-JWT [[link](https://github.com/firebase/php-jwt)]
   * A Firebase project for Cloud Messaging [[link](https://firebase.google.com/)]

## Setup

   * Import the **flavordex2.sql** file into a database using the method of your choice.
   * Rename **Config.php.sample** to **Config.php** (located in **web/Flavordex**).
   * Edit **Config.php** with your configuration parameters.
   * Place the contents of the **web/** directory in a Web accessible location.
   * If your server is not set up for SSL, remove `SSLRequireSSL` from **web/.htaccess**.

## License

The source code for the Flavordex API Server is released under the terms of the
[MIT License](http://sguidetti.mit-license.org/).
