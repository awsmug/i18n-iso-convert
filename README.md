# I18n ISO Convert

Convert ISO formats for countries to languages with the PHP function *i18n_iso_convert()* by including the file *i18n-iso-convert-class.php*.

###Example

```php
<?php
require_once ( 'i18n-iso-convert-class.php' );

// Converting form ISO 3166-1 alpha-2 (country) to ISO 693-1 (language)
$converted = i18n_iso_convert( '3166-1-alpha-2', '693-1', 'DK' ); // Returns 'DA' for ISO code 'DK' 
```

###Supported ISO Standards
At the moment there are supported the ISO standards for some countries

* ISO 3661-1 alpha 2
* ISO 3661-1 alpha 3
* ISO 693-1

###Adding more countries and languages

Feel free to fork the project and add missing countries, languages and standards. We would be glad if you would do a pull request on your changes, that we can add missing languages.

