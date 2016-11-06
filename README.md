# Magento2 LocaleRuUA
Add locale ru_UA to allowed locales list.

<img alt="Magento2 LocaleRuUA" src="https://karliuka.github.io/m2/locale-ru_ua/account.png" style="width:100%"/>
## Install with Composer as you go

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer require faonni/language-ru_ua
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
	php bin/magento setup:upgrade
	php bin/magento setup:static-content:deploy
    ```
