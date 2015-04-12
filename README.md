# MetaSEO - Search Engine Optimization for TYPO3

This extension provides an indexed google/xml-sitemap, enhanced metatag-support and pagetitel-manipulations for TYPO3.
It's an replacement of the "metatag"-extension and the successor of "tq_seo".

* Manual:     http://docs.typo3.org/typo3cms/extensions/metaseo/
* Git:        https://github.com/mblaschke/TYPO3-metaseo
* Support:    http://forge.typo3.org/projects/extension-metaseo/
* Bugtracker: http://forge.typo3.org/projects/extension-metaseo/issues

## Version status

* Version **1.x**:

  + Branch **master**
  + TYPO3 Version: 6.2.x
  + Composer: dev-master

* Version **2.x**:

  + Branch **develop**
  + TYPO3 Version: 6.2.x - 7.1.x
  + Composer: dev-develop


## Composer Support

MetaSEO (stable) is available **from TYPO3 TER** and also available with composer ::

    {
        "repositories": [
            { "type": "composer", "url": "http://composer.typo3.org/" }
        ],
        .......
        "require": {
            "typo3/cms": "6.2.*",
            "typo3-ter/metaseo": "*"
        }
    }

Or (unstable, don't blame me for bugs - but feel free to report bugs) directly **from Github** ::

    {
        "repositories": [
            { "type": "composer", "url": "http://composer.typo3.org/" },
            { "type": "vcs", "url": "https://github.com/mblaschke/TYPO3-metaseo.git" },
        ],
        .......
        "require": {
            "typo3/cms": "6.2.*",
            "mblaschke/metaseo": "dev-master"
        }
    }

## Contribution

If you want to contribute make sure you have an Editorconfig-Plugin installed in your IDE.
See [.editorconfig](.editorconfig) for indentation.

This TYPO3 Extension is using [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) as coding style.