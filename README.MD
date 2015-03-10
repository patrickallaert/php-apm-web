# APM (Alternative PHP Monitor) web frontend

[APM (Alternative PHP Monitor)](https://github.com/patrickallaert/php-apm) is a monitoring extension enabling native [Application Performance Management (APM)](http://en.wikipedia.org/wiki/Application_performance_management) for PHP.

This is the web frontend that enables visualizing the data gathered by that extension.

## Installing

### From source:

1. Check out this repository so that it can be accessed by your webserver.

    ```
    git clone https://github.com/patrickallaert/php-apm-web.git apm-web
    ```

2. Configure `config/db.php` to use the correct backend:

    ```php
    return new PDO("sqlite:/var/php/apm/db/events");
    ```
3. Reach the created directory from your browser: http://localhost/path/to/apm-web/

