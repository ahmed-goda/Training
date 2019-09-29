# Magento 2 Customer Testimonials Custom Module

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

Customer Testimonials is a hand tailored module designed for one of the hottest opensource technologies "Magento 2 CMS", that could be developed easily in a simple level.

  - [Requirements][RL1]
  - [Installation][IL1]
  - [Troubleshooting][TL1]
  - [License][LL1]

# Requirements:

- PHP >= 7.1.0
- Magento >= 2.3 Installed
- MySQL Server version 5.7.23 or higher || MariaDB version 10.2.7 or higher.
- Composer: 1.6.5 or higher.
- SERVER: Apache 2 or NGINX.


# Installation & Configuration :

- Step 1: Get the code
    - Clone the repository or Download and extract then create Training(vendor) directory or folder inside of the following path "<magento_root_dir>/app/code/". Inside the created vendor folder create one more as Testimonials(module name) and finally move all module's files into that directory.

- Step 2: Enable & activate the newely added module
    - Run following commands via terminal from magento root directory. Navigate to the root directory of the project  then execute these commands below as in their order:
    ```sh
    $ php bin/magento setup:upgrade
    $ php bin/magento setup:di:compile
    ```
    => Flush the cache and reindex all.
    and Hola!, the module now is properly installed.

Log in as admin to find a new menu has been added to the sidebar under the name Testimonials from which you can manage and manipulate the data.
Navigate to System menu then Data Transfer Section and finally Import item, to access the drop down list where you can upload the offline collated data as an Excel sheet or whatever CSV file format.

### Troubleshooting
Site loading very slow?
```sh
    $ php bin/magento setup:di:compile
    $ php bin/magento cache:clean
```

### License

This is free software is distributed under the terms of the MIT license.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [RL1]: <https://github.com/ahmedgodabytology/Training#Requirements>
   [IL1]: <https://github.com/ahmedgodabytology/Training#Installation>
   [TL1]: <https://github.com/ahmedgodabytology/Training#Troubleshooting>
   [LL1]: <https://github.com/ahmedgodabytology/Training#License>
   [LMDL1]: <https://github.com/ahmedgodabytology/Training/blob/master/LICENSE.md>