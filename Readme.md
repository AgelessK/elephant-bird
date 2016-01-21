# Ageless's Fork of Elephant Bird 

## About

[Elephant Bird](https://github.com/twitter/elephant-bird) is Twitter's open source library of [LZO](https://github.com/twitter/hadoop-lzo), [Thrift](http://thrift.apache.org/), and/or [Protocol Buffer](http://code.google.com/p/protobuf)-related [Hadoop](http://hadoop.apache.org) InputFormats, OutputFormats, Writables, [Pig](http://pig.apache.org/) LoadFuncs, [Hive](http://hadoop.apache.org/hive) SerDe, [HBase](http://hadoop.apache.org/hbase) miscellanea, etc. The majority of these are in production at Twitter running over data every day.

This repo is forked for patching the elephant-bird libs so that it can work on protobuf de/serialization correctly with
* Protobuf 2.5.0
* Hadoop 2.6.0
* Hive 1.2.1

## License

[Apache License, Version 2.0](http://apache.org/licenses/LICENSE-2.0).

