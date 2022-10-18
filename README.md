# Modern Theme
Modern theme for EspoCRM 7.x (ONLY TOP NAV SUPPORTED)

This theme replaces the Hub Inspired Theme

# Whats changed?
- Only css is changed, no templates no javascript
- LESS files included, nothing in Bootstrap is changed

# Installation
- Download archive as a zip file
- Unzip the zip file downloaded above
- Go to the module directory
- Zip files, scripts and manifest.json
- Go to the administration area of your Espo install
- Select plugins and click choose file
- Select the zip file you created in step 4
- Click upload
- Go to administration, user interface
- Select Modern Theme from the theme dropdown
- Logout, click ctrl and f5 to reload cache
- Login

# Upgrading
- Go to administration area of your Espo install
- Select user interface and set a stock theme as active
- Go to plugins and disable and uninstall Modern Theme
- Do installation steps above

# Before reporting a issue
- Make sure you've cleared Espos cache by running: php clear_cache.php
- Logout and login again
- Press CTRL + F5 to reload browser cache

# Customization (optional)
- Change all top nav icons to white
- Use the module\do_not_upload\email_templates\2fa_template.html as 2FA Code template
- Use the module\do_not_upload\email_templates\password_reset.html as Password Reset template
- Disable scope colors, tab colors and tab icons