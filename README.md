### This module provides better support for Workbench Moderation on nodes containing Field Collections. ###

Correctly sets the default revision status for Field Collection items to match the moderation status (published or otherwise) of the host node. This ensures that any Views using relationships to access Field Collection item fields will display fields from the published revision, instead of using fields from the latest revision. See [Most recent Field Collection revision always appears in View when using Workbench Moderation](https://drupal.org/node/1901892) for more detail.

### Requirements: ###

* [Workbench Moderation](https://drupal.org/project/workbench_moderation)
* [Field Collection](https://drupal.org/project/field_collection)

Note: the patch to Field Collection module at [Field collection doesn't play nice with workbench moderation (patch)](https://drupal.org/node/1807460#comment-7403212) is required if you are using Field Collection 7.x-1.x-beta7 or earlier.

This module wsa cloned from the sandbox project on [Drupal.org](https://www.drupal.org/sandbox/johnpitcairn/1991516)