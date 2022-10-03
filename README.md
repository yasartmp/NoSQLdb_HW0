# NoSQLdb_HW0

1.	ScyllaDB is a PA/EL highly available, partition tolerant, low latency system. ScyllaDB was designed to provide consistent low-latencies, not just be highly available, and it also provides tunable consistency. Under any conditions short of a complete system failure, ScyllaDB will remain highly available with predictable low latencies for mission critical applications.
ScyllaDB outperforms a distributed NewSQL database such as CockroachDB by a wide margin. Built for high availability, ScyllaDB still delivers tunable consistency, zero downtime, and high performance.  **(AP)**

https://www.scylladb.com/product/technology/high-availability/

2.	Arenadata DB (ADB) — аналитическая, распределённая СУБД, построенная на MPP-системе с открытым исходным кодом Greenplum. Она предназначена для хранения и обработки больших объёмов информации — до десятков петабайт. (аналогично greenplum & postgres - CA)  **(CA)**

https://arenadata.tech/products/arenadata-db/

3.	Dragonfly is a modern in-memory datastore, fully compatible with Redis and Memcached APIs. Dragonfly implements novel algorithms and data structures on top of a multi-threaded, shared-nothing architecture. As a result, Dragonfly reaches x25 performance compared to Redis and supports millions of QPS on a single instance.
Dragonfly's core properties make it a cost-effective, high-performing, and easy-to-use Redis replacement.

Исходя из описания БД и то, что Redis - **CP**, следжовательно Dragonfly тоже относится к этому же классу.

https://d7y.io/docs/v2.0.2/

![CAP classification](https://psv4.userapi.com/c237231/u406253434/docs/d36/6976b08f3273/CAP.png?extra=PWoYMsmU-uPUNdhu9OfjvRYTM9DNtlO3h1Tqh2odVA9hz0SY4KNMCpeKiZEVULNFF4bwFr7lAGv2nTS6arP-o1Psh5HG9JY9sZoq-nHM5uqWxEnbMaVSar5alXKhMPWSVtoYJgBPFSyBu7Rq443nWhL88po)
