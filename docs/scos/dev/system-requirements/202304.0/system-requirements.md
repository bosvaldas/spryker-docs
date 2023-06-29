---
title: System requirements
description: This document provides the configuration that a system must have in order for the Spryker project to run smoothly and efficiently.
last_updated: May 15 2023
template: howto-guide-template
originalLink: https://documentation.spryker.com/2021080/docs/system-requirements
originalArticleId: 6f7d36c1-2ee4-47d1-8f7f-ea0f1b7f93a7
redirect_from:
- /20220204/docs/system-requirements
- /20220204/docs/en/system-requirements
- /docs/system-requirements
- /docs/en/system-requirements
- /v6/docs/system-requirements
- /v6/docs/en/system-requirements
- /v5/docs/system-requirements
- /v5/docs/en/system-requirements
- /v4/docs/system-requirements
- /v4/docs/en/system-requirements
- /v3/docs/system-requirements
- /v3/docs/en/system-requirements
- /v2/docs/system-requirements
- /v2/docs/en/system-requirements
- /v1/docs/system-requirements
- /v1/docs/en/system-requirements
- /v4/docs/supported-browsers
- /v4/docs/en/supported-browsers
- /docs/scos/dev/setup/system-requirements.html
- /docs/scos/dev/setup/installing-spryker-with-development-virtual-machine/devvm-system-requirements.html
---
| REQUIREMENT | VALUE |
|---|---|
| OS                                        | Native: Linux                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Web Server                                | NginX—preferred. But any webserver which supports PHP will work such as lighttpd, Apache, Cherokee.                                                                                                                                                                                                                                                                                                                                                                   |
| Databases                                 | Depending on the project, one of the databases: MariaDB >= 10.4—preferred, PostgreSQL >=9.6, or MySQL >=5.7.                                                                                                                                                                                                                                                                                                                                                          |
| PHP                                       | Spryker supports PHP `>=8.0` with the following extensions: `curl`, `json`, `mysql`, `pdo-sqlite`, `sqlite3`, `gd`, `intl`, `mysqli`, `pgsql`, `ssh2`, `gmp`, `mcrypt`, `pdo-mysql`, `readline`, `twig`, `imagick`, `memcache`, `pdo-pgsql`, `redis`, `xml`, `bz2`, and `mbstring`. For details about the supported PHP versions, see [Supported Versions of PHP](/docs/scos/user/intro-to-spryker/whats-new/supported-versions-of-php.html) |
| SSL                                       | For production systems, a valid security certificate is required for HTTPS.                                                                                                                                                                                                                                                                                                                                                                                           |
| Redis                                     | Version >=3.2, >=5.0                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Elasticsearch                             | Version 7.*x*                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| RabbitMQ                                  | Version 3.6+                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Jenkins (for cronjob management)          | Version 1.6.*x* or 2.*x*                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Graphviz (for statemachine visualization) | 2.*x*                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Node.js                                   | Version >= 18.0.0                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| npm                                       | Version >= 9.0.0                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Intranet                                  | Back Office application (Zed) must be secured in an Intranet (using VPN, Basic Auth, IP allowlist, or DMZ).                                                                                                                                                                                                                                                                                                                                                            |
| Available languages                       | Spryker is available in the following languages:<ul><li>German</li><li>English</li></ul> Spryker offers full UTF-8 left-to-right language support.                                                                                                                                                                                                                                                                                                                    |