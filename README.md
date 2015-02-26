DHL2 WebAPI V2 Library
------------

This library is SDK for:
https://dhl24.com.pl/webapi2/doc/index.html


Usage
-----

```php

    $authData = new \Dhl\Structure\AuthData(USERNAME, PASSWORD);
    $dhlClient = new \Dhl\Client('http://sandbox.dhl24.com.pl/webapi2', $authData);

    $result = $dhlClient->getVersion();