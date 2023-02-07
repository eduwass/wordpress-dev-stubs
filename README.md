
## Install using Inteliphense (VSCode)

Clone this repo somewhere and add the path to the `inteliphense.stubs` setting in your `settings.json` file.

```json
"inteliphense.stubs": [
 "<path-to-this-repo>/",
]
```

## Rebuild stubs
```bash
git clone https://github.com/php-stubs/wordpress-stubs
git clone https://github.com/php-stubs/woocommerce-stubs
git clone https://github.com/php-stubs/acf-pro-stubs
rm -rf wordpress-stubs/.git
rm -rf woocommerce-stubs/.git
rm -rf acf-pro-stubs/.git
git add * -A
git commit -m "Update stubs"
git push
```

## Credits
This repo is a combination of the following repos:
- https://github.com/php-stubs/wordpress-stubs
- https://github.com/php-stubs/woocommerce-stubs
- https://github.com/php-stubs/acf-pro-stubs
