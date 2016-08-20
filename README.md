# Form auto fill
A simple drupal 8 form auto fill module.

Disclaimer:
This is a barebone only and there are no unit tests to check for data integrity.

Features:
 - Enable/disable switch.
 - Automatic fill: The entity forms are prefilled with randomized values.
 - Manual fill: A new button is added to the form where the user can press to fill the form with values.
 - Fields to fill settings: The user can select which fields to fill. Fields are separated in three categories: 'Label', 'Required' and 'Optional in form'.
 - This module only applies for when creating content and only for content entities.

 Usage:
 - Follow normal proceedures to download, place to the modules folder and activate.
 - Auto fill is activated by default.
 - Configure permissions to check if a user can control the module.
 - Go to '/admin/config/form_auto_fill/settings' to edit the settings.
 - Try to add a new content entity form.
 - Enjoy.