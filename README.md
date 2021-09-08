# customshippingcharge
Magento 2 plugin

This extension developed and tested on magento 2.2.3 CE 

Installation:
Download the extension.
keep the MagePsycho folde inside app/code folder
then run following commands from your terminal.

php bin/magento module:enable MagePsycho_Customshipping --clear-static-content
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:flush


After installation, go to Stores->Configuration->Shipping Methods->Custom Shipping
then, set YES to the enable field.