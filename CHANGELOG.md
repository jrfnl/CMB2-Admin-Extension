

## Changelog

### 0.1.3 beta 07.12.2016
* Tidying up and refactoring, thanks to phpcs and phpmd.

### 0.1.2 beta 06.29.2016
* PHP bug fixes. Props [@jrfnl](https://github.com/jrfnl)
* Fix language loading. Props [@jrfnl](https://github.com/jrfnl)
* Portuguese translation. Props [@pedro-mendonca](https://github.com/pedro-mendonca)

### 0.1.1 beta 06.26.2016
* Disable the group field type and the default option until support is added.

### 0.1.0 beta 06.26.2016
* Some much needed refactoring.

### 0.0.9 beta 06.26.2016
* Fix load_textdomain.

### 0.0.8 beta 06.26.2016
* Show hide option fields based on field type selected under the meta_box post type.

### 0.0.7 beta 06.25.2016
* Added support for the rest of the Custom, Field Attributes.

### 0.0.6 beta 06.23.2016
* Add option to select which taxonomy should be used for taxonomy based fields.

### 0.0.5 beta 06.23.2016
* Minor field output fixes.

### 0.0.4 beta 06.22.2016
* Simplify admin notices, this fixes fatal error.

### 0.0.3 beta 01.24.2016
* All thanks to [jrfnl](https://github.com/jrfnl)
* Synced the GH repo with the WP repo to make sure it was up to date.
* Removed some files from the repo which shouldn't have been there in the first place.
* The readme wasn't properly parsable for the WP repo, fixed that.
* Fixed the plugin header which referred to the wrong plugin.
* Use CMB2_LOADED constant to check for CMB2.
* Prefix the CMB2_PLUGIN_FILE constant so as not to confuse it with one coming from CMB2 native.
* Don't hard-code the path to the plugins directory.
* Properly encode variables used in the activation url.
* Don't add the $cmb2 variable to the global namespace.
* Prevent conflict in the global namespace by wrapping things in ! defined() and ! function_exists()
* Fixed the is_cmb2_allowed() function which did not allow for new installs. The result of that was that after activation the plugin no longer showed in the plugins list, didn't show in the admin menu, couldn't be used nor deactivated, so rendered itself effectively useless.
* Fixed undefined index notices. [See: https://wordpress.org/support/topic/not-working-1299](http://)
* Make settings page title translatable.

### 0.0.2 beta 06.15.2015
* Hide UI for disallowed users. Previously only hid plugin table rows.

### 0.0.1 beta 06.10.2015
* Initial release, is working but could use a lot more features.
