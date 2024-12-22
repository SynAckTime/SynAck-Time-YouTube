<h2>Nextcloud - Your Own Self Hosted Private Cloud and Collaboration Software</h2>

Check out our video where we explore Nextcloud and then walk you through the entire installation!

 [![Nextcloud - Your Own Self Hosted Private Cloud and Collaboration Software](https://img.youtube.com/vi/SNZP7pEx1T0/0.jpg)](https://www.youtube.com/watch?v=SNZP7pEx1T0)

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
