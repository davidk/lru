# lru

A fork of [groupcache](https://github.com/golang/groupcache)'s lru implementation, with mutexes added.

This was forked/modified for [chim](https://github.com/davidk/chim/), which does not handle the LRU cache in
a goroutine-safe manner, natively.
