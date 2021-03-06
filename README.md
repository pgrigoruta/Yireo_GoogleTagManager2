# Magento 2 module for Google Tag Manager
=========================================
Homepage: http://www.yireo.com/software/magento-extensions/googletagmanager2

Requirements:
* Magento 2.0.0 Stable

## Installation
We recommend `composer` to install this package. See our [COMPOSER.md](COMPOSER.md) instructions.

If you want a manual copy instead, these are the steps:
* Upload the files in the `source/` folder to the folder `app/code/Yireo/GoogleTagManager2` of your site
* Run `php -f bin/magento module:enable Yireo_GoogleTagManager2`
* Run `php -f bin/magento setup:upgrade`
* Flush the Magento cache
* Configure settings under `Stores > Configuration > Sales > Yireo GoogleTagManager`
* Done

## Unit testing
This extension ships with PHPUnit tests. The generic PHPUnit configuration in Magento 2 will pick up on these
tests. To only test Yireo extensions, simply run PHPUnit from within this folder. Note that this assumes that
the extension is installed via composer. For instance:

    phpunit
