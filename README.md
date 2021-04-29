# oxid_patches
How many times you have thought about OXID and "Do you want to ..." -> YES 
Don't do it again!

# first add this to your main composer file
composer require cweagans/composer-patches

# add this to your main composer file
    "extra": {
      "patches": {
        "oxid-esales/oxideshop-composer-plugin": {
          "Don't ask, simple install all new": "https://raw.githubusercontent.com/fleurami/oxid_patches/main/OxidAskYes.patch"
        }
      },
      "enable-patching": true
    },

# run this command
composer install

Enjoy!
