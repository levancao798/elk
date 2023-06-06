# Quick way to test logstash config file 
```
bin/logstash -f configfile.conf --config.reload.automatic
```
or
```
sudo bin/logstash --config.test_and_exit -f <path_to_config_file>
```
# Filebeat test config
```
[root@localhost ~]# filebeat test config
Config OK
```
```
filebeat test output -c /etc/filebeat/filebeat2.yml
```
test output
```
filebeat test output
```