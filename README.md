# Magento2 Twitter Bootstrap Javascript

Add Twitter Bootstrap javascript from CDN as a require.js module shim. With fallback to local version when CDN is offline.

## Installation

1. `composer require timneutkens/magento2-module-twitterbootstrap-js`  
will install the latest version. If you want a specific Twitter Bootstrap version you can use this:
`composer require timneutkens/magento2-module-twitterbootstrap-js:<version here>`

2. Run `bin/magento setup:upgrade`

3. Run `bin/magento setup:static-content:deploy`

### Available versions

- 3.3.7

## Usage

```javascript
require(['jquery', 'jquery.bootstrap'], function ($) {
  $('.element').carousel()
});
```