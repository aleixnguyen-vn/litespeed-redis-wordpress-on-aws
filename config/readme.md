## 📂 Config Files

This repository includes actual configuration files used in this stack:

- `php.ini`: default LiteSpeed PHP config (no custom tuning)
- `redis.conf`: 256MB maxmemory, allkeys-lru eviction
- `vhost.conf`: Virtual host adapted from OpenLiteSpeed structure
- `wp-config.php.sample`: Redis object cache + `WP_CACHE` enabled
- `loaderio.txt`: Loader.io verification file for concurrency testing
