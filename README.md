# opencart-admin-token-remover

Admin Token Remover for OpenCart

## Install

1. Back up `/storage/modification` folder;
2. Copy `admin_token_remover.ocmod.xml` file to `/system` directory;
3. Update modification cache and login again.

## Uninstall

2. Remove `admin_token_remover.ocmod.xml` file from `/system` directory;
3. Update modification cache and login again.

## Issues

Q. Session timeout changed to 1 hour\
A. Check `session.cookie_lifetime` directive

Q. Can't login into admin panel\
A. Make sure that cookies enabled in your browser

## License

This source file is subject to the Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)

It is also available through the world-wide-web at this URL:\
https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
