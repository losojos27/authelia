---
layout: default
title: MySQL
parent: Storage backends
grand_parent: Configuration
nav_order: 2
---

# MySQL

```yaml
storage:
    mysql:
        host: 127.0.0.1
        port: 3306
        database: authelia
        username: authelia
        # This secret can also be set using the env variables AUTHELIA_STORAGE_MYSQL_PASSWORD
        password: mypassword
```
