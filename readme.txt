=== Simple Cloudflare Turnstile — The new user-friendly alternative to CAPTCHA ===
Contributors: ElliotVS, RelyWP, Severino
Tags: cloudflare,turnstile,captcha,protect,spam
Donate link: https://www.paypal.com/donate/?hosted_button_id=RX28BBH7L5XDS
Requires at least: 4.7
Tested up to: 6.2
Stable Tag: trunk
License: GPLv3 or later.
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Add Cloudflare Turnstile to WordPress, WooCommerce, Contact Forms & more. The user-friendly, privacy-preserving reCAPTCHA alternative. 100% free!

== Description ==

Easily add Cloudflare Turnstile to all your WordPress website forms to protect them from spam!

A user-friendly, privacy-preserving reCAPTCHA alternative.

## Supported Forms ##

You can currently enable Turnstile on the following forms:

**WordPress**

* Login Form
* Registration Form
* Password Reset Form
* Comments Form

**WooCommerce**

* Checkout
* Pay For Order
* Login Form
* Registration Form
* Password Reset Form

**Form Plugins**

* WPForms
* Fluent Forms
* Contact Form 7
* Gravity Forms
* Formidable Forms
* Forminator Forms

**Other Integrations**

* Elementor Pro Forms
* Easy Digital Downloads Forms
* Mailchimp for WordPress Forms
* BuddyPress Registration Form
* bbPress Create Topic & Reply Forms
* Ultimate Member Forms
* WP-Members Forms
* wpDiscuz Custom Comments Form

## What is Cloudflare Turnstile? ##

Cloudflare Turnstile delivers frustration-free, CAPTCHA-free web experiences to website visitors.

Turnstile stops abuse and confirms visitors are real without the data privacy concerns or awful UX that CAPTCHA thrusts on users.

Learn more here: <a href="https://www.cloudflare.com/en-gb/products/turnstile/" target="_blank">https://www.cloudflare.com/en-gb/products/turnstile/</a>

## Getting Started ##

It's super quick and easy to get started with Cloudflare Turnstile!

1. Simply generate a "site key" and "secret key" in your Cloudflare account, and add these in the plugin settings page.
2. Select which forms Turnstile should be added to and click save.
3. Finally, click the "TEST API RESPONSE" button to make sure the Turnstile API response is working OK.
4. A new Cloudflare Turnstile challenge will then be displayed on your selected forms to protect them from spam!

For more detailed instructions, please see our <a href="https://relywp.com/blog/how-to-add-cloudflare-turnstile-to-wordpress/" target="_blank">setup guide</a>.

## Is it free to use? ##

Yes, this plugin is completely free with no paid version, and it doesn't track your data. Cloudflare Turnstile is also a completely free service!

Please consider helping out by <a href="https://wordpress.org/support/plugin/simple-cloudflare-turnstile/reviews/#new-post">leaving a review</a>, or <a href="https://www.paypal.com/donate/?hosted_button_id=RX28BBH7L5XDS">donate</a>.

## Languages ##

Currently available in <a href="https://translate.wordpress.org/projects/wp-plugins/simple-cloudflare-turnstile/" target="_blank">8 languages</a>. Thank you to all the <a href="https://translate.wordpress.org/projects/wp-plugins/simple-cloudflare-turnstile/contributors/" target="_blank">contributers</a>! If you would like to help contribute translations, please <a href="https://translate.wordpress.org/projects/wp-plugins/simple-cloudflare-turnstile/" target="_blank">click here</a>.

## Other Information ##

* For help & suggestions, please <a href="https://wordpress.org/support/plugin/simple-cloudflare-turnstile/#new-topic-0" target="_blank">create a support topic</a>.
* Follow the developer <a href="https://twitter.com/ElliotSowersby" target="_blank">@ElliotSowersby</a> on Twitter.
* <a href="https://github.com/elliotvs/simple-cloudflare-turnstile" target="_blank">View on GitHub</a>

== Installation ==

1. Upload 'simple-cloudflare-turnstile' to the '/wp-content/plugins/' directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Visit the plugin settings in WordPress admin menu at "Settings > Cloudflare Turnstile".
4. You will need to generate a "Site Key" and "Site Secret" in your Cloudflare account, then enter these in the settings page.
5. Select which forms you want to enable Turnstile on, then click the "Save Changes" button.
6. Finally, you will be required to complete a quick test of the widget by clicking "TEST API RESPONSE", to confirm it's working correctly.
7. A new Cloudflare Turnstile challenge will then be displayed on your selected forms to protect them from spam!

For more detailed instructions, please see our <a href="https://relywp.com/blog/how-to-add-cloudflare-turnstile-to-wordpress/" target="_blank">setup guide</a>.

https://www.youtube.com/watch?v=Yn8X_GsTFnU

== Screenshots ==

1. Example Turnstile on the WP Login Page
2. Example Turnstile on the WP Register Page
3. Example Turnstile on the WP Comments Form
4. Example Turnstile on the WooCommerce My Account Page
5. Example Turnstile on the WooCommerce Checkout Page
6. Example Turnstile on a Contact Form
7. Example Settings Page

== Changelog ==

= Version 1.18.6 - 22th May 2023 =
- New: Added option that may be activated to require the user to comply that the data is pulled and verified from cloudflare (opt-in). 
- Tweak: Renamed the 'cfturnstile.css' to 'cf_wpdiscuz.css' and added a 'cf_turnstile.css' that is always loaded.

= Version 1.18.5 - 27th April 2023 =
- Fix: Fixed error on admin settings page for new installs, since last update.

= Version 1.18.4 - 27th April 2023 =
- Tweak: Made some tweaks to the admin settings page design.
- Tweak: Added check for Easy Digital Downloads PRO.
- Tweak: Turnstile will now work/be displayed on the Elementor login form.
- Tweak: Tweak to alignment of Turnstile on wpDiscuz comments form and added a "wpdiscuz-cfturnstile" class for applying any custom CSS/alignment tweaks if needed.
- Fix: Fixed occasional error with Contact Form 7 not re-rendering Turnstile on form submission error.
- Fix: Fixed issue with Gravity Forms when AJAX form was enabled, where if submitting with an error, Turnstile would not re-render.
- Fix: Fixed issue with Turnstile still not loading on some Forminator forms that had "Load form using AJAX" enabled.
- Fix: Fixed issue with Ultimate Member login form occasionally failing on first attempt with Turnstile enabled.
- Fix: Fixed WooCommerce integration settings sometimes not showing properly if Payment Method names were too long.

= Version 1.18.3 - 13th April 2023 =
- Fix: Fixed issue with Turnstile not loading on Forminator forms with "Load form using AJAX" enabled.
- Fix: Fixed broken settings link on plugins list since last update.

= Version 1.18.2 - 11th April 2023 =
- New: Added option to remove all the plugins options on uninstall.
- Tweak: Updated the admin settings page URL slug.
- Fix: Fixed issue with admins not being able to reply to comments on the /wp-admin/edit-comments.php page.
- Fix: Fixed an issue with wpDiscuz integration since 1.18.1 update.

= Version 1.18.1 - 10th April 2023 =
- Tweak: Update to make compatible with certain other login security plugins, or any other plugins that run the login "authenticate" multiple times.
- Tweak: Fixed issue with Turnstile widget showing on all Elementor forms (not just contact forms) and prevent it from showing twice.
- Tweak: Update to offer better compatibility with AJAX comment form plugins.

= Version 1.18.0 - 9th April 2023 =
- New: Added integration with the "Easy Digital Downloads" plugin.
- New: Added integration with the "WP-Members" plugin.
- New: Added compatibility with "Blocksy" theme login modal.
- New: Added option to skip Turnstile check for selected WooCommerce payment methods. Useful for Express Checkout options.
- Tweak: Improvements to code for displaying Turnstile on Elementor forms.
- Tweak: Added check to prevent Turnstile check when adding WooCommerce users in admin area.
- Tweak: Make tweak to ensure Turnstile challenge is checked for some 3rd-party plugins that load the login form.
- Tweak: Added "cfturnstile_cf7_button_types" filter for applying custom button types for the Contact Form 7 integration.
- Tweak: Made some tweaks to the admin settings page design.
- Tweak: Added code for declaring of compatibility with WooCommerce HPOS.
- Fix: Turnstile will now render properly on comment "reply" and "cancel reply" buttons being clicked.

= Version 1.17.3 - 10th March 2023 =
- Tweak: The "Language" setting options are now localized.
- Tweak: The "cfturnstile.css" file is now only loaded when required.
- Fix: Added a check to prevent PHP warning when there is an API error.

= Version 1.17.2 - 24th February 2023 =
- New: Added support for the new "data-language" attribute available with Turnstile. A default language can now be selected in the settings.
- Tweak: Added "data-action" attribute to Turnstile widget, which will allow you to see more detailed analytics in your Cloudflare dashboard.
- Tweak: Some improvements to code (added universal "cfturnstile_form_disable" function).
- Tweak: Added NULL check to force render script.
- Fix: Fixed "Uncaught TypeError" JS error when Turnstile enabled on comments form.
- Fix: Fixed potential console error due to unknown parameter sent to Cloudflare API.
- Fix: Fixed issue with multisite compatibility.

= Version 1.17.1 - 27th December 2022 =
- Tweak: Edited the filter used for WooCommerce login authentication, and fixed Turnstile challenge being checked twice when both WP Login and Woo Login enabled.

= Version 1.17.0 - 20th December 2022 =
- New: Added integration for the WooCommerce "Pay for Order" form.
- New: Added "Disabled Form IDs" option for "Forminator Forms" integration.
- Tweak: Added "After Form" option to elementor forms integration "Widget Location" setting. This will display the widget better on certain types of form layouts.
- Tweak: When submitting WPForms form, if there is an error, the Turnstile widget will now reset and re-verify.
- Tweak: On Elementor forms, wpDiscuz forms, and Forminator forms, Turnstile will now re-render on submission.
- Tweak: The code for the "Disable Submit Button" option now uses vanila javascript instead of jQuery, and the JS file will only be loaded if the option is enabled.
- Tweak: Turnstile on WordPress login will now work better with plugins that hide/change the admin login URL.
- Tweak: WordPress Login and Register will skip Turnstile check for XMLRPC requests.
- Tweak: Edited the filter used for WordPress login authentication.
- Fix: Fixed issue with Turnstile widget not showing in some cases with the Contact Form 7 integration "Enable on all CF7 Forms" option enabled, since CF7 version 5.7.
- Fix: Fixed "Disable Submit Button" not working with the new "Forminator" plugin integration.
- Fix: Fixed "One or more fields have an error." message sometimes showing on Contact Form 7 integration with Turnstile enabled.
- Fix: Fixed issue with the "bbPress" integration "alignment" option no longer working, since a recent update.

= Version 1.16.0 - 8th December 2022 =
- New: Added integration with the "Forminator" plugin.
- Tweak: Added a check in the scripts for showing Turnstile on Elementor, to prevent a possible console error.
- Fix: Fixed error with Turnstile widget not showing on Elementor forms with the "Before" option selected for "Widget Location".

= Version 1.15.4 - 30th November 2022 =
- Tweak: Implemented the new "data-retry-interval" attribute for Turnstile widget when displayed on Elementor forms.
- Fix: Turnstile widget now works properly with multiple Elementor forms on the same page, as long as each form has a unique "name".

= Version 1.15.3 - 27th November 2022 =
- Fix: Fixed Turnstile widget no longer rendering for some sites with certain optimisations enabled since 1.15.0 update.

= Version 1.15.2 - 26th November 2022 =
- Fix: Fixed "Call to undefined function is_plugin_active()" error showing on some sites since 1.15.0 update.

= Version 1.15.0 - 26th November 2022 =
- New: Added option to choose where exactly the Turnstile widget is displayed on WooCommerce checkout. Also updated code so adding it directly before the place order button now works.
- Tweak: Turnstile widget will now re-render on WooCommerce checkout, if any changes are made (checkout cart info reloads via js/ajax).
- Tweak: Minified the inline script for rendering Turnstile, and this now uses vanila javascript instead of jQuery.
- Tweak: Updated all forms to have completely unique Turnstile IDs, even if same form is displayed twice on same page (popups etc). This should prevent issues with Turnstile not loading properly on one of them.
- Tweak: Integrations should now work properly on WordPress multisite installations.
- Tweak: Implemented the new "data-retry-interval" attribute for Turnstile widget when displayed on WordPress comments.
- Other: Removed some redundant code for the "cfturnstile_scripts" option that was removed previously.

= Version 1.14.0 - 17th November 2022 =
- New: Added option to enable Turnstile on ALL forms created with Contact Form 7, instead of having to add it individually.
- Tweak: Implemented the new "data-retry-interval" attribute to speed up time it takes to retry on failure.
- Tweak: Turnstile will now work better/correctly with multiple forms displayed on the same page.
- Fix: Fixed error with Turnstile enabled on CF7 multi-step forms.
- Other: Tested with WordPress 6.1.1

= Version 1.13.2 - 11th November 2022 =
- Fix: Changed the code for wpDiscuz integration, so Turnstile loads properly for comment replies, and only attempt to enqueue scripts once.

= Version 1.13.1 - 4th November 2022 =
- Fix: Fixed Turnstile widget not showing on comments form for some sites that have certain optimisations enabled.

= Version 1.13.0 - 4th November 2022 =
- New: Added integration with "Ultimate Member" login, register, and password reset forms.
- Fix: Fixed 'Unknown parameter passed to api.js: "?ver=..."' console warning that was showing.

= Version 1.12.4 - 3rd November 2022 =
- Fix: Fixed a bug with widget showing twice for contact form 7 on some sites.

= Version 1.12.3 - 3rd November 2022 =
- Fix: Added check to see if jQuery is undefined, and fix error if so.

= Version 1.12.2 - 2nd November 2022 =
- Tweak: Removed "Where to load scripts?" option, since it will now accurately only load the scripts on pages that Turnstile is showing.
- Tweak: Tweaks to the WordPress comments validation code.
- Other: Tested with WordPress 6.1

= Version 1.12.1 - 30th October 2022 =
- Fix: Fixed a bug/issue on settings page for new installs (since last update).

= Version 1.12.0 - 30th October 2022 =
- New: Added "Disabled Form IDs" option for "Fluent Forms", "Gravity Forms", "WPForms", and "Formidable Forms" integrations.
- New: Added a "Widget Location" option to the "Formidable Forms" and "Elementor Forms" integrations.
- New: Added option to set your own custom error message, shown when the user submits the form with a failed Turnstile challenge.
- Tweak: A few small changes to the admin settings page.
- Fix: Fixed "PHP Deprecated" warning with Elementor integration enabled.

= Version 1.11.0 - 29th October 2022 =
- New: Added integration with "Formidable" forms. Simply enable it in the settings, and Turnstile will be added to all your forms.

= Version 1.10.0 - 28th October 2022 =
- New: Added integration with "Elementor" Pro forms. Simply enable it in the settings, and Turnstile will be added to all your forms.

= Version 1.9.0 - 28th October 2022 =
- New: Added integration with "wpDiscuz" plugin.

= Version 1.8.6 - 27th October 2022 =
- New: Added a "Widget Location" option to the "WPForms" and "Gravity Forms" integrations, to choose if the widget is shown before or after the button.
- Tweak: Updated alignment of Turnstile widget when displayed on frontend pages (moved 2px to left).

= Version 1.8.5 - 27th October 2022 =
- Tweak: It will now only try to re-render Turnstile widget explicitly (embedded JavaScript) if it can't currently find the Turnstile widget iFrame.

= Version 1.8.4 - 26th October 2022 =
- New: Added a fourth "Auto Detect + Custom Page IDs" option to the "Where to load scripts?" setting.
- Improvement: Updated the admin settings page to only show settings/dropdowns for integrations that are available (plugins activated and installed). A compact list of the other available integrations is still visible at the bottom.
- Dev: Updated some of the comments in the code to be more readable.

= Version 1.8.3 - 25th October 2022 =
- New: Added a third "Custom Page IDs" option to the "Where to load scripts?" setting. This lets you enter the specific page IDs that you want the scripts to load on.

= Version 1.8.2 - 24th October 2022 =
- New: Added option to select where the Turnstile script is loaded. Either "Auto Detect" or "All Pages".
- Tweak: "Auto Detect" will also load the required scripts on blog posts that include forms.

= Version 1.8.1 - 24th October 2022 =
- Fix: Fixed issue with admins not being able to reply to comments in the admin area, when Turnstile was enabled on the comments form.

= Version 1.8.0 - 24th October 2022 =
- New: Added integration with "Gravity Forms" plugin. Simply enable it in the settings, and Turnstile will be added to all your forms.
- Tweak: Added some code to ensure the Cloudflare widget is rendered when sites have certain optimisations enabled.
- Fix: Fixed error with WPForms emails still being sent if Turnstile fails.

= Version 1.7.0 - 22nd October 2022 =
- New: Added integration with "Fluent Forms" plugin. Simply enable it in the settings, and Turnstile will be added to all your forms.
- Tweak: Improved alignment of the Turnstile widget when displayed on Contact Form 7.
- Fix: Fixed a string that was missing localisation.

= Version 1.6.2 - 21st October 2022 =
- Fix: Fixed some strings that were missing localisation.
- Fix: Fixed "Cannot modify header information – headers already sent" error showing on some sites when activating plugins.

= Version 1.6.1 - 21st October 2022 =
- Tweak: Small tweaks to admin settings page styling.
- Fix: Fixed to the "Test API Response" step. It should now properly block Turnstile from loading on the login page until it's successfully tested (new activations only).

= Version 1.6.0 - 21st October 2022 =
- New: Added integration with "bbPress" create topic and reply forms.
- New: Added a new "Test API Response" step to the settings page, whenever the API keys are updated to make sure it's working. Turnstile will not work on your login forms until the test is successfully complete.
- Tweak: Changed the way the error message is shown for WordPress comments.
- Fix: Fixed issue with Turnstile verification not working correctly on checkout if "Create an account?" was selected.

= Version 1.5.1 - 20th October 2022 =
- Tweak: Removed the "Disable Submit Button" feature for the "WooCommerce Checkout" form button, to prevent issues with it sometimes not working.
- Fix: Fixed "Call to undefined function is_plugin_active()" error showing on some sites.
- Fix: Fixed styling/scripts not loading on admin page on first load.

= Version 1.5.0 - 20th October 2022 =
- New: Added integration with "WPForms" plugin. Simply enable it in the settings, and Turnstile will be added to all your forms.
- Tweak: Updated the design of admin settings page slightly.
- Fix: Fixed issue causing "Disable Submit Button" option to not work on some sites.

= Version 1.4.0 - 19th October 2022 =
- New: Added integration with "MC4WP: Mailchimp for WordPress". You can now add Turnstile to any MC4WP form. Just add the shortcode: [mc4wp-simple-turnstile]

= Version 1.3.0 - 18th October 2022 =
- New: Added integration with "BuddyPress" registration form.
- Other: Restructured some of the code.

= Version 1.2.2 - 18th October 2022 =
- Tweak: Upon submitting checkout form, if there is an error, it will now automatically reset Turnstile challenge token.

= Version 1.2.1 - 18th October 2022 =
- Tweak: Update so the the required scripts are only loaded on pages that need it.
- Tweak: Added an "Auto" option to the "Theme" setting.
- Tweak: Upon submitting contact form 7, it will now automatically reset Turnstile challenge token.
- Fix: Fixed some strings with wrong text domain, that could not be translated.
- Fix: Fixed settings link in plugins list not working.

= Version 1.2.0 - 17th October 2022 =
- New: Added integration with "Contact Form 7". You can now add Turnstile to any CF7 forms. Just add the shortcode: [cf7-simple-turnstile]

= Version 1.1.2 - 17th October 2022 =
- New: Added a "Disable Submit Button" option. When enabled, the submit button for all forms will be disabled until the Turnstile widget says "Success".
- Tweak: The turnstile script will now load correctly when using a custom wp-login URL.
- Tweak: Added a redirect to settings page on activation.
- Tweak: Hidden WooCommerce form settings if it is not installed or activated.

= Version 1.1.1 - 15th October 2022 =
- Fix: Fixed PHP error sometimes showing when WooCommerce is not installed.

= Version 1.1.0 - 15th October 2022 =
- New: Added option to enable Turnstile on WordPress comments form.

= Version 1.0.0 - 15th October 2022 =
- Plugin Released
