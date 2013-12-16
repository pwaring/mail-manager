Mail Manager
============

Mail Manager is an abstraction layer to allow student projects to send email whilst imposing rate limits to prevent simple mistakes - e.g. a mass email to external addresses.

Primarily intended for use within the School of Computer Science at the University of Manchester.

See `example.php` for a simple example of how to use the class.

This class assumes you have a file `config.inc.php` somewhere within your path which sets the following global variables:

```
$database_host
$database_user
$database_pass
$database_name
```