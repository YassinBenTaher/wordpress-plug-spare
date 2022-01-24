# Spare Payment Method For Wordpress

This is a Spare Checkout Payment Method for WooCommerce.

## Requirements

  * WordPress 4.4 or greater
  * wooCommerce plugin
  * Composer 2.x

## Installation (manuel)

  * Install wooCommerce plugin through the __Admin Panel__ 
  * Download the Plugin Module , unpack it and upload its contents to a new folder ```<root>/wp-content/plugins/spare-payment/``` of your wordpress installation
  * Install Spare PHP API Library

    ```sh
    $ composer require bty/php-sdk
    ```

## Configuration

  * Login inside the __Admin Panel__ and go to ```Woocommerce``` -> ```Setting``` -> ```Payments```
  * In the Installed Payement methods list, activate the Spare Gateway method
  * Click the button ```Manage``` right side the payment method ```Spare Gateway``` to open the available settings
  * Tick ```Enable Spare Gateway``` , set the correct credentials, select your prefered transaction types and additional settings and click ```Save configs```