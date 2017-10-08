# Magento 2 French (fr_FR) Language Pack

*French Language* is your native language and you need to use that language on your magento 2 store. Please follow this article, **Magento 2 French Language Pack** from Magento 2 translation project. The README will help you get French pack and install it fluently.

## Overview

- Download
- How to Install French Language Pack
- How to active language pack

## Download the French Language Pack

**Download packages**:

- [Download .zip](https://github.com/SubrataBauri/magento2-french-language-pack/archive/master.zip)

## How to Install French Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method (recommended)
Install the French language pack via composer is never easier.

**Install French pack**:

```
composer require subrata/magento2-french-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  French pack**:

```
composer update subrata/magento2-french-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

![Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the French language pack
- Step 2: Unzip French pack
- Step 3: Upload
- Step 4: Flush Magento 2 Cache

#### Step 1 : Download the French language pack

You can download the language pack from above links

#### Step 2: Unzip French pack

Unzip the French language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

### #3. Download and install manually

To download and install French pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/SubrataBauri/magento2-french-language-pack/archive/master.zip)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `fr_FR.csv` into `app/i18n/subrata/fr_FR/fr_FR.csv`

#### Step 2: Flush cache


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 French language pack}}](https://i.imgur.com/aPSUA0l.png)


<!-- ## Translation process of French Language Pack
![process](http://progressed.io/bar/80) -->


## Supported Magento versions

- Magento v2.1.*

