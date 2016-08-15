# cqlsh

##### This fork exposes a new command line parameter `--protocolversion` from the original `cqlsh` in case there is a mismatch w.r.t default protocol version set in cqlsh vs the cassandra installation.

##### Usage :
```bash
cqlsh localhost --cqlversion="3.2.1" --protocolversion="3"
cqlsh localhost --cqlversion="3.2.1" --protocolversion="4"
```


### Note: This is a mirror of cqlsh from the official [Cassandra repo](http://git-wip-us.apache.org/repos/asf/cassandra.git).

If you would like to contribute to cqlsh, [find out more information here](http://wiki.apache.org/cassandra/HowToContribute).

`cqlsh` is a Python-based command-line client for running CQL commands on a Cassandra cluster.  This script and the associated libraries come bundled with Apache's Cassandra installer.  This repo is a re-bundled version that allows for `cqlsh` to be used on a machine separate from that running Cassandra or from inside a virtual environment.

Documentation is available in the [Apache Cassandra(TM) 2.0 documentation](http://www.datastax.com/documentation/cassandra/2.0/webhelp/index.html#cassandra/gettingStartedCassandraIntro.html).
