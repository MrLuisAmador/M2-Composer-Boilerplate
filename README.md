# M2-Composer-Boilerplate

In the root Magento folder, run this command

```
composer require mrluisamador/m2-composer-boilerplate dev-master
```

You will be asked to authenticate yourself to connect to Magento:

[Get your authentication keys](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

Once that is done the base theme will be installed and located in the *vendor* folder at:

```
vendor/your_package/m2-composer-boilerplate
```

## Notes:

Although the Magento documentation will display examples in the `app/design/frontend/` folder, this all proves to work the same
with the base theme being in the vendor directory because of the *registration.php*. 

Follow the same direction as the Magento documentation. The only difference is the location of the theme.

## For Instruction on how to use the theme, Please read the wiki page.

[Base theme instructions](https://github.com/MrLuisAmador/M2-Composer-Boilerplate.git)