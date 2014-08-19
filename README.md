Research Square Opauth Strategy
===============================

[Opauth][1] strategy for Research Square authentication. Opauth is a multi-provider authentication framework for PHP.

Getting started
----------------
1. Install Opauth-ResearchSquare using Composer:

    ```json
    {
        "require": {
            "researchsquare/opauth-researchsquare": "dev-master"
        }
    }
    ```

2. Create a Research Square application, taking note of your client_id and client_secret.
   
3. Configure Opauth-ResearchSquare strategy.

4. Direct user to `http://path_to_opauth/researchsquare` to authenticate.


Strategy configuration
----------------------

Required parameters:

```php
<?php
    'ResearchSquare' => array(
        'client_id' => 'YOUR CLIENT ID',
        'client_secret' => 'YOUR CLIENT SECRET'
    )
```

License
---------
Opauth-ResearchSquare is MIT Licensed  
Copyright © 2014 Research Square (http://www.researchsquare.com)

[1]: https://github.com/uzyn/opauth
