# eZ Platform Marketing Automation Bundle

This bundle integrates [Net-Result’s marketing automation](http://www.net-results.com/) suite into the eZ Publish
Platform.

## License
See the LICENSE file that ships at the root of this bundle.

## Installation

1. add the following to your composer.json:
```
{
    "require": {
        "ezsystems/marketing-automation-bundle": "dev-master",
        ...
    },
    ...
    "repositories": [
        {
            "type": "vcs",
            "url":  "git@github.com:ezsystems/MarketingAutomationBundle.git"
        }
    ]
}
```

2. run `composer update ezsystems/marketing-automation-bundle`.

3. Add `new EzSystems\MarketingAutomationBundle\EzSystemsMarketingAutomationBundle()` to your kernel (`ezpublish/EzPublishKernel.php`).