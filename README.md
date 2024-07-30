# unique_events
Count unique events using HyperLoglog
1. Docker compose for zk and kafka and mysql (to store events) and redis (for hll) (done)
2. Events producer python script (done)

3. KStreams app for processing the events
4. Create RedisSink/Processor for counting unique events using HLL.
5. Write the HLL to database (key, value store)
6. Roll up from 5 min to higher  (PFMERGE)
7. REST API to query unique users over different time ranges.