---
title: memcached
type: cache
---

<!--
     THIS FILE IS AUTOGENERATED!

     To make changes please edit the contents of:
     lib/cache/memcached.go
-->


```yaml
memcached:
  addresses:
  - localhost:11211
  prefix: ""
  retries: 3
  retry_period: 500ms
  ttl: 300
```

Connects to a cluster of memcached services, a prefix can be specified to allow
multiple cache types to share a memcached cluster under different namespaces.

