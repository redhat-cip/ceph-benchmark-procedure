ceph-benchmark-procedure
========================

Set of tools to properly benchmark a Ceph cluster.


RADOS Benchmark Generator
=========================

Simple bash script to execute several rados bench patterns.

Future improvments:

* Configurable result directory
* Add support for multiple PG num
* Use ksh to drop_cache (faster than async ssh flushes)
