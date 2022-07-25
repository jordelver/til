---
date: "2022-01-16"
title: Something something
subtitle: Something
---
# Restarting individual Docker compose services

Docker compose makes it easy to specify services that can all be started
together. However, sometimes it's useful to restart a single service to avoid
having to restart everything. For example, you might have `api` and `redis`
services.

To restart just the API.

```shell
docker compose restart api
```
