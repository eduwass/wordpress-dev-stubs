git clone https://github.com/php-stubs/wordpress-stubs
git clone https://github.com/php-stubs/woocommerce-stubs
git clone https://github.com/php-stubs/acf-pro-stubs
rm -rf wordpress-stubs/.git
rm -rf woocommerce-stubs/.git
rm -rf acf-pro-stubs/.git
git add * -A
git commit -m "Update stubs"
git push
