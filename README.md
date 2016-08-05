# Magento2 Twitter Bootstrap Javascript

Add Twitter Bootstrap javascript from CDN as a require.js module shim. With fallback to local version when CDN is offline.

## Installation

1. `composer require timneutkens/magento2-module-twitterbootstrap-js`

2. Run `bin/magento setup:upgrade`

3. Run `bin/magento setup:static-content:deploy`

## Usage

```javascript
require(['jquery', 'jquery.bootstrap'], function ($) {
  $('.element').carousel()
});
```