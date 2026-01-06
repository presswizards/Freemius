# Freemius Integration for FreeScout
This module is designed to integrate Freemius with FreeScout.

Download the ZIP file, upload it to your FreeScout Modules folder, extract the folder, and very important, be sure to rename it to just "Freemius", do not try activating it named "Freemius-master", it will not work. Once extracted and renamed to "Freemius", activate the module.

To configure the global module settings, go to Manage > Settings > Freemius, and enter your Freemius details found in your Freemius dashboard:

- Freemius Developer ID
- Freemius Public key
- Freemius Secret key

Once the module is configured, the Customer data from Freemius is displayed in the sidebar on the Customer editing and ticket pages (if it is found there).
The first opening of the Customer page may take longer than usual, as requests are sent to Freemius.

## Requires
- PHP CURL extension

## INSTALL
- Place module source to Modules folder of your FreeScout installation, be sure it is renamed to "Freemius".
- Activate module in modules admin panel
- Configure module on settings page `Manage->Settings->Freemius`
