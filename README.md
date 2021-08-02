# Julien_ManageOffers
This module allows the creation of new offer on category page view.
The offer button is present in content -> element section.

## 1. How to install.

## ✓ Install via composer
Run the following command in Magento 2 root folder:
```
composer config repositories.juli0s vcs https://github.com/Juli0s/manage-offers
composer require juli0s/manage_offers
php bin/magento module:enable Julien_ManageOffers
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```
