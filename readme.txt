=== Clean Login ===
Contributors: hornero, carazo
Donate link: http://codection.com
Tags: form, login, registration, editor, lost password, responsive, wmpl, internationalization, languages, role, CAPTCHA, honeypot,  shortcode, wordpress, frontend
Requires at least: 3.4
Tested up to: 3.9.1
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A plugin for displaying useful forms in front-end only using shortcodes. Login, Registration, Profile Editor and Lost Password forms

== Description ==

## **Basics**

*   Add your login form in the frontend easily (page or post)
*   And also the registration and the lost password form
*   If user is logged in, the user will see a custom profile and will be able to edit his/her data in another front-end form
*   One shortcode per form, you only need to create a page or post and apply this shortcode to create each form you want

## **Style**

*   Every form created is Responsive
*   CSS adapted to every theme

## **Spam protection**

*   Register form protected with CAPTCHA (as an option)
*   Forms are also protected by Honeypot antispam protection

## **Internacionalization**

*   WMPL ready
*   po/mo template included

## **More features**

*   Auto status checker
*   Hide admin bar for non-admin users as an option
*   Disable dashboard access as an option
*   Standby user role for new user registration. With no capabilities, to allow admin approval of users optionally
*   Auto linked forms, if you place a shortcode in a page/post the link between them will be automatically generated
*   And yes, this is WordPress 3.9 ready! Also compatible with WooCommerce.

You could test it here [cleanlogin.codection.com](http://cleanlogin.codection.com/). Enjoy!

== Usage and Settings ==

Please, refer to [./documentation/index.html#settings](documentation/index.html#settings)

== Screenshots ==

1. Login form
2. Preview user
3. Editor form
4. Lost password form
5. Register form with CAPTCHA
6. Setting access from the dashboard
7. Setting page from the dashboard

== Changelog ==

= 1.0.1 =
*   Banner created
*   Screenshots added
*   Demo site for testing purposes

= 1.0.0 =
*   First release

== Upgrade Notice ==

= 1.0 =
*   First installation

== Demo site ==

[cleanlogin.codection.com](http://cleanlogin.codection.com/)

== Frequently Asked Questions ==

*   Not yet

== Installation ==

There are two ways of install the plugin:

*   Unzip the zip file you downloaded from codecanyon.net. Open it, copy the 'clean-login' folder and place in your web server WordPress plugins directory using any FTP Client such as&nbsp;[CUTEFtp](http://www.cuteftp.com/),&nbsp;[WS-FTP](http://www.wsftple.com/)&nbsp;or&nbsp;[FileZilla](https://filezilla-project.org/), or else follow the step below
*   Log in to your WordPress administration panel then click Add New in the Plugins menu on the left side and click on the Upload link at the top of the page then Locate and upload the plugin zip archive that you extracted after downloading the package.

Then, after the package is uploaded and extracted, click&nbsp;_Activate Plugin_.

Now going through the points above, you should now see a new&nbsp;_Clean Login_&nbsp;menu item under Settings menu in the sidebar of the admin panel, see figure below of how it looks like.

<img src="http://plugins.svn.wordpress.org/clean-login/assets/doc/menu.jpg" alt="Menu" />

If you get any error after following through the steps above though then please contact us through item support comments so that i can get back to you with possible helps in installing the plugin. On successful activation of this plugin, you should be able to see the login form when you place this shortcode&nbsp;_[clean-login]_&nbsp;in any page or post

* * *

### **Settings**

Below, the description of each shortcode for use as registration, login, lost password and profile editor forms

*   _[clean-login]_ This shortcode contains login form and login information.
*   _[clean-login-edit]_ This shortcode contains the profile editor. If you include in a page/post a link will appear on your login preview.
*	_[clean-login-register]_ This shortcode contains the register form. If you include in a page/post a link will appear on your login form.
*	_[clean-login-restore]_ This shortcode contains the restore (lost password?) form. If you include in a page/post a link will appear on your login form.

Also, in the Clean Login settings page you can check the plugin status as follows:

![](assets/doc/status.jpg)

In this setting page you can also find the way to enable/disable the differents options of the plugin, like below:

![](assets/doc/options.jpg)

Regarding the widget usage, just place the&nbsp;_Clean Login status and links_&nbsp;widget in the widget area you prefer. It will show the user status and the links to the pages/posts which contains the plugin shortcodes.

Please feel free to contact us if you have any questions.

* * *

### **Example**

A post/page need to be created by typing the main shortcode&nbsp;_[clean-login]_&nbsp;in the content, as follows:

![](assets/doc/example.jpg)

When you save or update this post/page you will see the login form:

![](assets/doc/login_form.jpg)

And also in the setting page&nbsp;_[clean-login]_&nbsp;entry will be updated pointing to the current post/page which contains the shortcode (and generates the login form):

![](assets/images/settings_updated.jpg)

We would repeat the same process with the rest of shortcodes if we need it:

*   _[clean-login-edit]_&nbsp;to create an edit profile form
*   _[clean-login-register]_&nbsp;to create a registration form
*   _[clean-login-restore]_&nbsp;to create a forgotten password and restore form