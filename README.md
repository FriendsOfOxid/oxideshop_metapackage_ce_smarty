OXID eShop metapackage (Smarty based)
=====================================

This repository contains the most basic OXID eShop dependencies.

More information how to setup Shop:

  - https://docs.oxid-esales.com/developer/en/7.2/getting_started/installation/eshop_installation.html

## Important note

Smarty isn't supported by OXID eShop from 7.1, use is at your own risk.

OXID eShop 7.4 is the final release line for which FriendsOfOxid provides this Smarty metapackage. This package is no longer officially supported or maintained from OXID eShop 7.4 onward. Third-party support for Smarty has also become increasingly difficult to obtain. Existing installations may continue to use it at their own risk, but no further updates or support are planned. For new installations, use the standard Twig-based OXID eShop metapackage.

## Differences to the original metapackage

- no strict definition of 3rd party dependencies - allows the installation of e.g. security patches without shop updates
- optional modules are not included, can be installed later if required
- Smarty template renderer