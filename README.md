# opencart-admin-token-remover

Admin Token Remover for OpenCart, compatible with ocStore

## Editions

* [OpenCart 3](https://github.com/doctorOC/opencart-admin-token-remover)
* [OpenCart 2](https://github.com/doctorOC/opencart-admin-token-remover/tree/opencart-2.x)

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

Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)

It is also available through the world-wide-web at this URL:\
https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
