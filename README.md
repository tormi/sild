# Drupal ping helper
[![Build Status](https://travis-ci.org/wunderio/drupal-ping.svg?branch=master)](https://travis-ci.org/wunderio/drupal-ping) [![Latest Stable Version](https://poser.pugx.org/wunderio/drupal-ping/v/stable)](https://packagist.org/packages/wunderio/drupal-ping) [![Total Downloads](https://poser.pugx.org/wunderio/drupal-ping/downloads)](https://packagist.org/packages/wunderio/drupal-ping) [![Latest Unstable Version](https://poser.pugx.org/wunderio/drupal-ping/v/unstable)](https://packagist.org/packages/wunderio/drupal-ping) [![License](https://poser.pugx.org/wunderio/drupal-ping/license)](https://packagist.org/packages/wunderio/drupal-ping)

This script can be used for Drupal7 healthchecks.

## Installation
Add this to your composer.json:

```json
{
    "repositories":
    {
        "type": "git",
        "url": "https://github.com/tormi/sild"
    }
}
```

```json
{
    "extra": {
        "dropin-paths": {
            "web/": ["type:web-dropin"]
        }
    }
}
```

Then install the composer package as usual with
```
composer require tormi/sild:7.x-dev
```


## Maintainers
[Janne Koponen](https://github.com/tharna)

## License
MIT
