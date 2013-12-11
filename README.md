## Overview
ChromePhp is a PHP library for the Chrome Logger Google Chrome extension.

This library allows you to log variables to the Chrome console and is ready for the CodeIgniter framework.

## Requirements
- PHP 5 or later

## Installation
1. Install the Chrome extension from: https://chrome.google.com/extensions/detail/noaneddfkdjfnfdakjjmocngnfkfehhd
2. Click the extension icon in the browser to enable it for the current tab's domain
3. Put ChromePhp.php in `application/libraries`
4. Log some data

    ```php
    $this->load->library('chromephp');
    $this->chromephp->log('Hello console!');
    $this->chromephp->log($_SERVER);
    $this->chromephp->warn('something went wrong!');
    ```

More information can be found here:
http://www.chromelogger.com
