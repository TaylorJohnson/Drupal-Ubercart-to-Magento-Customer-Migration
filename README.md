Drupal Ubercart to Magento Customer Migration
=============================================

This simple module exports customers from Drupal and generates a CSV file suitable for import into Magento.

The module makes many hardcoded assumptions about many aspects regarding the customers such as website, store, group, etc.

Drupal
1) Place the user_import folder into your Drupal /sites/all/modules/ directory.
2) Enable the module in Drupal
3) Navigate to (yoursite)/admin/store/customers/user_export
Magento
4) Navigate to System > Import > Import
5) Follow prompts and upload file for import