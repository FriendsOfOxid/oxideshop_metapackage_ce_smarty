OXID eShop metapackage (Smarty based)
=====================================

This repository contains the most basic OXID eShop dependencies.

More information how to setup Shop:

  - https://docs.oxid-esales.com/developer/en/7.0/getting_started/installation/eshop_installation.html
  
## Differences to the original metapackage

- no strict definition of 3rd party dependencies - allows the installation of e.g. security patches without shop updates
- optional modules are not included, can be installed later if required
- Smarty template renderer