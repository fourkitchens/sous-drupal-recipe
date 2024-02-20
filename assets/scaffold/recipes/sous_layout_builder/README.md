# Sous Layout Builder Drupal Recipe
A recipe that contains modules and configuration for Sous default layout builder configuration.

## Configuring Drupal for Recipes

See https://www.drupal.org/files/issues/2023-10-01/Configuring%20Drupal%20to%20Apply%20Recipes.md

## Installing this Recipe

`composer require sous-starter/sous_layout_builder`

## Applying this Recipe

If you used the Sous Project as your starterkit:
- `lando install-recipe sous_layout_builder`

Manually applying the recipe to your own project:
From your webroot run:
- `php core/scripts/drupal recipe recipes/sous_layout_builder`
- `drush cr`
- `composer unpack fourkitchens/cookbook:sous_layout_builder`
