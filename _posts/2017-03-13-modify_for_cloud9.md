---
title:  "Jekyll on Cloud9 Configurations"
date:   2017-03-13 07:29:23
categories: [Cloud9 Modifications]
tags: [how-to, introduction, cloud9-configs]
---

Cloud9 allows users to run many different web-servers, including the Jekyll Static Web Page Server (With some slight configurations!).

Simply add the lines below to the `_config.yml` file if they are not already present.

```yml
# Modifications for Cloud9 Development.
port: 8080
host: 0.0.0.0
```

See Cloud9's [documentation](https://docs.c9.io/docs/run-an-application) for more information.
