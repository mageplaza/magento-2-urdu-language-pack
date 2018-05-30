## Magento 2 Urdu Language Pack

How to install **Magento 2 Urdu Language Pack** on Magento 2 store? The best explanation will be pointed out in this topic with the same topic that is built by Mageplaza team. The post allows replacing the default language (English) by the native one (Urdu). That is great idea when your business is growing in Pakistan. Thanks to that, you will gain the expectable results in the conversion.

In this guide, not only the installation guide, you are also directed how to get the translation file through clicking on "Download .zip" button. All requirements to apply the Urdu on the entire store are referred fully and apparently. Take a look at the post now!

Read more [Magento 2 Urdu Language Pack](https://www.mageplaza.com/magento-2-urdu-language-pack.html)


## Overview

- Download & Contribute
- Install Urdu Language Pack
- How to Install Urdu Language Pack

## 1. Download & Contribute to Urdu Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Urdu Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-urdu-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-urdu-language-pack/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Urdu Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Urdu language pack via composer is never easier.

**Install Urdu pack**:

```
composer require mageplaza/magento-2-urdu-language-pack:dev-master
php bin/magento setup:static-content:deploy ur_PK
php bin/magento cache:flush

```


**Update  Urdu pack**:

```
composer update mageplaza/magento-2-urdu-language-pack:dev-master
php bin/magento setup:static-content:deploy ur_PK
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Urdu language pack
- Step 2: Unzip Urdu pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Urdu language pack

You can download the language pack from above link

#### Step 2: Unzip Urdu pack

Unzip the Urdu language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/i18n/Mageplaza/ur_pk
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Urdu pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-urdu-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-urdu-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `ur_PK.zip` into `app/i18n/mageplaza/ur_PK/ur_PK.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Urdu language pack

Now time to active the Urdu language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Urdu language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

Contribute to this language at https://crowdin.com/project/magento-2/ur-PK

## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 Open-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## 6. Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-urdu-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References:

- https://www.mageplaza.com/magento-2-urdu-language-pack.html
- https://crowdin.com/project/magento-2








## Mageplaza extensions on Magento Marketplace, Github



☞ [Blog](https://github.com/mageplaza/magento-2-blog)

☞ [Social Login](https://github.com/mageplaza/magento-2-social-login)

☞ [SEO](https://github.com/mageplaza/magento-2-seo)

☞ [SMTP](https://github.com/mageplaza/magento-2-smtp)

☞ [Product Sliderthub](https://github.com/mageplaza/magento-2-product-slider)

☞ [Banner](https://github.com/mageplaza/magento-2-banner-slider)

☞ [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



