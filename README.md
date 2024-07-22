# SW Secure Deploy

Security configs and deployment tips for a secure Shopware 6 setup.

## Links

- [Shopware 6 Security](https://docs.shopware.com/en/shopware-6-en/tutorials-and-faq/security-measures)
- [Two Factor Authentication plugin](https://github.com/runelaenen/shopware6-two-factor-auth)
- [Update Shopware](https://www.thomaspeissl.com/blog/posts/2024-04-29-update-shopware-6-with-composer-update-no-scripts/)

## Usage

- Add code from [.htaccess](.htaccess) to your `.htaccess` file.  
**Note:** to ensure the code is not overwritten by WordPress, place it outside the # BEGIN Shopware and # END Shopware tags.
- Enable Two Factor Authentication

## Recommendations

- Use a creative admin user name
- Install extensions as composer packages
- You should always keep up to date with the latest version of Shopware and extensions
- Verify the backups are working

## Advanced

- Change the admin url slug to an arbitrary string using the SHOPWARE_ADMINISTRATION_PATH_NAME env variable
- Strict rate limits with shopware.yml
