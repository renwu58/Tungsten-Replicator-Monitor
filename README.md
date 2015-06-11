# Tungsten-Replicator-Monitor
Tungsten Replicator Monitor

This is a efficiency tools for monitor Tungsten Replicator service status.

### How to deploy it
1. Setting a configuration file contain all service need monitor
  The configuration file like this:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Tungsten>
        <service>
                <name>odstest</name>
                <path>/home/ss/tungsten/odstest</path>
        </service>
</Tungsten>
```
2. Start the monitor<br>
```shell
  `bash monitor.sh --monitor`
```
