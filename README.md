# Zabbix
zabbix

# Increase Log information
```console
zabbix_server --runtime-control log_level_increase
```

# Reload server conf
```console
zabbix_server -R config_cache_reload
```

# Watch zabbix 
```console
watch -n 0.2 ps -fu zabbix
```
