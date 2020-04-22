webform_migrate 8.x
-------------------

### About this Module

This module provides migration routines from Drupal 6, Drupal 7 webforms to Drupal 8 webform.

### Installing the Webform Migrate Module
- webform_migrate

### Configure:

- Make sure your legacy webform module is up to date. So update your D7 or D6 webform module first.
- Copy the "migration_templates" YAML files and import them into Drupal configs either using Configuration Management UI or Drush/Drupal Console.


### Common errors
- If you get a warning about an extension `d7_webform` or `d7_webform_submission` on config import, and you are on a newer drupal 8 version, you can try renaming the files to `webform_migrate.d7_webform.yml` (etc.)
