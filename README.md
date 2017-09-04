thor-firewall-logger
========================================

firewall event logging via nflog netlink and [ulogd2](https://www.netfilter.org/projects/ulogd/) userspace daemon

```raw
  _____ _   _  ___  ____       _____ _                        _ _
 |_   _| | | |/ _ \|  _ \     |  ___(_)_ __ _____      ____ _| | |
   | | | |_| | | | | |_) |____| |_  | | '__/ _ \ \ /\ / / _` | | |
   | | |  _  | |_| |  _ <_____|  _| | | | |  __/\ V  V / (_| | | |
   |_| |_| |_|\___/|_| \_\    |_|   |_|_|  \___| \_/\_/ \__,_|_|_|
```

## Features ##

* Efficient SQL Logging Scheme
* **Multi Host** Log Aggregation using dedicated sql-user
* Designed to be used with [mariadb](https://mariadb.org) or [mysql](https://mysql.com)
* Created as component of [thor-firewall](https://github.com/AenonDynamics/thor-firewall)

## Todo ##

* Replace **ulogd** with **GO** based netlink->mariadb gateway..

## Requirements ##

* **ulogd v2**
* **mysql/mariadb** server
* **mysql/mariadb** libraries
* **netfilter nflog** support

## Installation ##


## Distributions ##

Tested with:

* Debian Jessie 8.7
* Debian Stretch 9.0
* Debian Stretch 9.1


## License ##
THOR-FIREWALL-LOGGER is OpenSource and licensed under the Terms of [The MIT License (X11)](http://opensource.org/licenses/MIT) - your're welcome to contribute