# Topics to Learn for Redis
## 1. Introduction & Basics
- What is Redis? (In-memory data store, caching, message broker)
- Redis architecture (single-threaded model, event loop)
- [Installing Redis (local, Docker, cloud)](#)
- Redis CLI basics (redis-cli, configuration, commands)
- Understanding redis.conf file

## 2. Data Types & Operations
- Strings: SET, GET, INCR, APPEND
- Lists: LPUSH, RPUSH, LRANGE, LPOP, RPOP
- Sets: SADD, SMEMBERS, SINTER, SUNION
- Sorted Sets (ZSets): ZADD, ZRANGE, ZRANK, ZREM
- Hashes: HSET, HGET, HGETALL
- Bitmaps: SETBIT, GETBIT, BITCOUNT
- HyperLogLog: PFADD, PFCOUNT
- Streams: XADD, XREAD, XGROUP

## 3. Key Management
- Key expiration: EXPIRE, TTL, PERSIST
- Pattern matching: SCAN, KEYS
- Key naming conventions & best practices
- Deleting data: DEL, UNLINK

## 4. Persistence & Durability
- RDB (Snapshotting): configuration & performance
- AOF (Append Only File): configuration & recovery
- Hybrid persistence (RDB + AOF)
- Backup & restore strategies

## 5. Pub/Sub & Messaging
- PUBLISH / SUBSCRIBE
- Pattern-based subscriptions (PSUBSCRIBE)
- Use cases (real-time notifications, chat apps)

## 6. Transactions & Atomicity
- MULTI, EXEC, DISCARD, WATCH
- Optimistic locking
- Ensuring atomic operations

## 7. Replication & High Availability
- Master-slave replication
- Read replicas
- Redis Sentinel for failover
- Redis Cluster basics (sharding, slots)

## 8. Security
- Redis AUTH & ACLs
- Network-level security
- Running Redis behind a firewall / in private networks

## 9. Advanced Features
- Redis Modules (RedisJSON, RedisSearch, RedisGraph, RedisBloom)
- Geospatial indexes (GEOADD, GEORADIUS)
- Stream processing with consumer groups
- Custom commands with modules

## 10. Performance Optimization
- Memory optimization (maxmemory, eviction policies)
- Pipelining (MULTI/EXEC vs pipelining)
- Lua scripting in Redis
- Connection pooling

## 11. Monitoring & Troubleshooting
- Redis MONITOR, INFO, SLOWLOG
- Log analysis
- Memory usage inspection
- Debugging blocking operations

## 12. Real-world Integrations
- Using Redis with Python, Node.js, Java, Go, etc.
- Redis as a cache in front of databases
- Redis for rate limiting
- Redis for leaderboard systems
- Redis as a message queue
