marmotta-titan
==============

Titan Graph DB backend for Apache Marmotta

## Configuartion
In the Marmotta ```properties``` file simply add the configuration properties that you usually use for Titan and prepend it with ```titan.``` prefix.

For example a configuration for a ```Titan Graph``` with a ```HBase``` backend at ```192.168.1.1```:
```
titan.storage.backend = hbase
titan.storage.hostname = 192.168.1.1
```

For more configuration options of Titan check [here](https://github.com/thinkaurelius/titan/wiki/Graph-Configuration)
