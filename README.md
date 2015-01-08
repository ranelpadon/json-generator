# json-generator
Input data using admin forms, then output the saved data in JSON format.

This is a simplified module to promote the importance of hook_menu, hook_form, system_settings_form, variable_set, and variable_get, and the ease of outputting Drupal data in JSON format. Security checks and other details are intentionally omitted to focus on the core concepts and the bigger picture of custom module development.

You could conveniently download the [zipped file](https://github.com/ranelpadon/json-generator/archive/master.zip) from [GitHub](https://github.com/ranelpadon/json-generator). Just rename the unzipped module folder to **json_generator** (note that underscores should be used instead of dashes) before using it to you Drupal site.

### HOW TO USE
After installing the module and assuming your site is http://www.example.com:

1. Input some text in this URL: http://www.example.com/admin/config/json_generator
2. Then, see the generated JSON data here: http://www.example.com/json_generator

Since the generated data is in JSON format (which is a universal data),
it could then be used by Drupal and non-Drupal sites using JavaScript/jQuery.
