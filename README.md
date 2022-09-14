# Test & Clean FishPig Rekoobe Infection

If you suspect your FishPig modules are infected with Rekoobe, run the following commands to test:

Run the check from the Magento installation dir with a single line:

```php <(curl -s https://raw.githubusercontent.com/bentideswell/magento2-rekoobe-cleaner/main/bin/fishpig_rekoobe_clean)```

Or if you would rather install the package...

First install this package:

```composer require fishpig/magento2-rekoobe-cleaner```

Nex run the command to test:

```vendor/bin/fishpig_rekoobe_clean```
