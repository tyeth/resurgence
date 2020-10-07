# Resurgence theme for Drupal 8

Intended to be used with the following drupal modules:
* layout_builder
* focal_point
* media
* image_slider
* social_media_links

# Install with (from drupal composer root):
```composer require drupal/social_media_links drupal/focal_point drupal/image_slider```

```vendor/drush/drush/drush en focal_point social_media_links crop media_library layout_builder image_slider```

# migrating between environments:
https://drupal.stackexchange.com/questions/150481/how-can-i-import-the-configuration-on-a-different-site

You can get the UUID with:

```drush config-get "system.site" uuid```

And you can change it with

```drush config-set "system.site" uuid "fjfj34-e3bb-2ab8-4d21-9100-b5etgetgd99d5"```