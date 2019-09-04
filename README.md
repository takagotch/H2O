### h2o
---
https://github.com/h2o/h2o

https://www.h2o.ai/

```c
// src/httpclient.c

static h20_httpclient_connection_pool_t *connpool;

static h2o_httpclient_head_cb_cb on_connect(h2o_httpclient_t *client, const char *errstr, h2o_iovec_t *method, h2p_url_t *url,
  const h2o_header_t **headers, size_t *num_headers, h2o_iovec_t *body,
  h2o_url_t * origin);
  
static void on_exit_deferred(h2o_timer_t *entry)
{
  h2o_timer_unlink(entry);
  exit(1);
}

```

```
```

```
```


