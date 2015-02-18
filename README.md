# gravity-forms-wcag-20-form-fields
https://wordpress.org/support/plugin/gravity-forms-wcag-20-form-fields

Modifies Gravity Forms form fields and improves validation so that forms meet WCAG 2.0 accessibility requirements.

== Description ==

Extends the Gravity Forms plugin - modifies form fields and improves validation so that forms meet WCAG 2.0 accessibility requirements.

**What does this plugin do?**

* Wraps radio, checkbox and list (repeater) fields in a fieldset.
* Improves form validation by displaying an alert message and on-page message that describes how many errors there were in the page. On-page message contains a list of the form fields with the errors, a description of the error and a link to the field.
* Adds aria-describedby attributes for date and website fields - providing clear instructions for screen reader users of what format is required for the field.
* Adds HTML5 'required' attribute and aria-required='true' for required fields
* Adds aria-describedby attributes for fields that have failed validation - providing clear instructions for screen reader users of what the field error is. Description used is the default validation message for the field, or if set, the validation message for the field.
* Disables the Gravity Forms configured tabindex - this stops users from being able to tab between fields and on-page links.

**How to I use the plugin?**

Simply install and activate the plugin - no configuration required.

**Have a suggestion or request?**

Please leave a detailed message on the support tab. 

**Please note:**

* Accessibility is a complicated topic and sometimes there are different opinions on how to best achieve an accessible website. Accessible forms are even harder to achieve, with many different approaches. 
* This plugin does not cover other aspects of accessibility, such as content order, clear instructions, colour contrast etc.
* You will also need to ensure that your websites theme is accessible. 

== Changelog ==

= 1.2.2 =

* Enqueue stylesheet instead of directly printing to page.
* Replace i18n slug with slug string instead of class reference.
* Fix text strings for internationalization.
* Fix bug with <fieldset> failing to be inserted.
* Add ARIA live attribute to form validation error
* Remove JS alert to avoid redundant notifications with ARIA

== Installation ==

1. This plugin requires the Gravity Forms plugin, installed and activated
2. Install plugin from WordPress administration or upload folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in the WordPress administration
4. The radio, checkbox and repeater list fields will now be automatically modified so that they meet the accessibility requirements.

== Frequently Asked Questions ==

**I still see errors on my form**

Whilst this plugin goes a long way to taking a Gravity Form towards WCAG 2.0 compliance, there are still some things that haven't been looked at yet.

If you're having troubles or even better know a solution, please leave a detailed message on the support tab.
