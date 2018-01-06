# Magento2 Sample Module
This is an example module with Create Admin menu and controller In Magento2
## Manually Installation

Magento2 module installation is very easy, please follow the steps for installation-

=> Download and unzip the respective extension zip and create Webkul(vendor) and Hello(module) name folder inside your magento/app/code/ directory and then move all module's files into magento root directory Magento2/app/code/Webkul/Hello/ folder.

## Install with Composer as you go
Specify the version of the module you need, and go.
    
    composer config repositories.reponame vcs https://github.com/webkulabhi/magento2_sample_module
    composer require webkulabhi/magento2_sample_module:dev-master
    

## Run following command via terminal from magento root directory 
  
     $ php bin/magento setup:upgrade
     $ php bin/magento setup:di:compile
     $ php bin/magento setup:static-content:deploy

=> Flush the cache and reindex all.

now module is properly installed

## Code explanations 

https://webkul.com/blog/create-hello-module-in-magento2
