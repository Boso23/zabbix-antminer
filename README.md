# zabbix-antminer

## antminer-zabbix-check

Note: `antminer-zabbix-check` script uses `curl` and `jq` (make sure to install them)

Returns data in less than 0.03 seconds.

```
$ time ./antminer-zabbix-check 192.168.88.249 4028 stats "GHS 5s"
"828.68"

real    0m0.028s
user    0m0.008s
sys     0m0.000s
```

## zbx_templates_antminer_*.xml

Zabbix: Configuration -> Templates -> Import -> Import
