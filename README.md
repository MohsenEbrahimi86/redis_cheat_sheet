# Redis Cheat Sheet
A simple cheat sheet for Redis


# Basic Types:
* String
* Integer  
Basic data types are generally sets by:
`SET name value`
  
example for String:  
`SET url "www.someurl.com"`  
`SETNX url "www.someurl.com"`  

example for Integers:  
`SETNX hits 23`  
`INCR hits`  

# Stack and Queue
L refers to first of the list
R refers to last of the list
LPUSH
RPUSH
LPOP
RPOP

LRANGE 0 -1
LLEN

#Sets
SADD
SREM
SISMEMBER
SMEMBERS
SUNION

# Ordered Set
ZADD
ZREM

//Hashes
HSET user:1000 name "jack" email "jack.smith@example.com" 
HGETALL user:1000
HGET user:1000 name

You can try redis commands here:
[TRY REDIS COMMANDS](http://try.redis.io/).
