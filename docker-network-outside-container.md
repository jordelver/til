---
date: "2022-07-26"
title: Something something
subtitle: Something
---
If you need to refer to something running on your host machine such as a
database server like MySQL or PostgreSQL from your Docker container on macOS you
can use `host.docker.internal`

For example, for Redis:

    host.docker.internal:6379
