# Auto Instagram Post - Magento 2
---

This Magento 2 extension Auto Instagram Post allows you add your products immediately to Instagram after publishing it on Magento site, share your thoughts, product information, brand news and latest  to your friends.

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/thinghost)
![Version 1.1.1](https://img.shields.io/badge/Version-1.1.1-green.svg)

---
## [![Alt GhoSter](http://thinghost.info/wp-content/uploads/2015/12/ghoster.png "thinghost.info")](http://thinghost.info) Overview

- [Extension on GitHub](https://github.com/tuyennn/AutoInstagramPost)
- [Direct download link](https://github.com/tuyennn/AutoInstagramPost/tarball/master)


![Alt Screenshot-1](http://thinghost.info/wp-content/uploads/2017/08/Selection_426-1024x487.jpg "thinghost.info")
![Alt Screenshot-2](http://thinghost.info/wp-content/uploads/2017/08/Selection_424-1024x530.jpg "thinghost.info")
![Alt Screenshot-3](http://thinghost.info/wp-content/uploads/2017/08/Selection_425-1024x456.jpg "thinghost.info")
![Alt Screenshot-4](https://thinghost.info/wp-content/uploads/2015/12/Selection_489.jpg "thinghost.info")
![Alt Screenshot-5](https://thinghost.info/wp-content/uploads/2015/12/Selection_490.jpg "thinghost.info")

## Main Features

* Use Instagram API to post main Product Image of store to Instagram
* Support configurations with #hashtag.
* Support sort content of comment as user defined.
* Support Manage Products Grid mass Action to Post or rePost to Instagram

## Configure and Manage

* Enable Auto Instagram - Enable or disable module.
* Username - Your Instagram Username.
* Password - Your Instagram Password.
* Default Image - When you add a product without a main Image to store, this image will be uploaded to Insragram.
* Allow auto posting to Instagram after Saving Product - Enable Observer after product saved
* Enable Auto Hashtag and Description on Instagram Post - Enable below options
* Enable Auto Product Description - This will add product description to your feature post.
* Enable Custom Hashtag - Your custom hashtags go there.
* Enable Auto Categories name as Hashtag - This will add product category as hashtag to your feature post.
* Instagram Post Description Template - This will define the order of content which you want to post.

## Installation with Composer

* Connect to your server with SSH
* Navigation to your project and run these commands
 
```bash
composer require ghoster/autoinstagrampost


php bin/magento setup:upgrade
rm -rf pub/static/* 
rm -rf var/*

php bin/magento setup:static-content:deploy
```

## Installation without Composer

* Download the files from github: [Direct download link](https://github.com/tuyennn/AutoInstagramPost/tarball/master)
* Extract archive and copy all directories to app/code/GhoSter/AutoInstagramPost
* Go to project home directory and execute these commands

```bash
php bin/magento setup:upgrade
rm -rf pub/static/* 
rm -rf var/*

php bin/magento setup:static-content:deploy
```
## Licence

[Open Software License (OSL 3.0)](http://opensource.org/licenses/osl-3.0.php)


## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/thinghost)
