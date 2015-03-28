##MemcachedModule

There are some modules in memcached, writen in c++.

####Install

```
cd memcache_event
make
```

```
cd memcache_slab
make
```

####memcache_event

Memcached event module, contains a worker and some threads, using libevent and pipe.

* libevent
* pipe
* threads
* list

####memcache_slab

Memecached memory module, contais memory_allocate and delete.

* limit
* factor
* slab list
* split mem
