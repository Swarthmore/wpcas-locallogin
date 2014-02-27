wpcas-locallogin
================

Plugin to integrate WordPress or WordPressMU with existing CAS single sign-on architectures. Based largely on Stephen Schwink's CAS Authentication plugin. Optionally, you can set a function to execute when a CAS username isn't found in WordPress. 

Functionality has been added to allow for optional local login.

Originally Authored by Casey Bisson
Modified by Les Leach


From Casey Bisson's original installation instructions:

1. Download phpCAS and place it on your webserver so that it can be included by the wpCAS plugin.
2. Place the plugin folder in your wp-content/plugins/ directory and activate it.
3. Set any options you want in Settings -> wpCAS or in the wpcas-conf.php file.
4. The plugin starts intercepting authentication attempts as soon as you activate it. Use another browser or another computer to test the configuration.
