<h1>Memory Caching for Nextcloud</h1>

<h2>Redis config (Optional)</h2>

```
'memcache.locking' => '\OC\Memcache\Redis',
'memcache.distributed' => '\OC\Memcache\Redis',
'memcache.local' => '\OC\Memcache\Redis',
'redis' => [
 'host' => 'redis',
 'port' => 6379,
  ],
```

<h2>APCu</h2>

```
'memcache.local' => '\OC\Memcache\APCu',
'memcache.distributed' => '\OC\Memcache\Memcached',
```
