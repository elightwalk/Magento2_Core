# Name :

=> Elightwalk core module.


# Descriptions :

=> Elightwalk_Core extension provides the basic requirements for other elightwalk modules.


# Installation :

Go to Magento root and then below **commands**

```
 composer require elightwalk/magento2_core
 php bin/magento module:enable Elightwalk_Core
 php bin/magento setup:upgrade
 php bin/magento setup:di:compile
 php bin/magento c:f
 php bin/magento c:c

```

# Supporting Versions :

```
  => 2.4.6, 2.4.5

```

# Changelog

## 1.0.2

    => Add a "Configuration" menu to maintain the configuration of other module.

## 1.0.1

    => Restore quote api and graphql implement.
