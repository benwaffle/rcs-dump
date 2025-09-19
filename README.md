# Notes

## Google Messages debugging

```
setprop log.tag.BugleRcsEngine VERBOSE
```

Enable PII logging with
```
# sqlite3 /data/data/com.google.android.gms/databases/gservices.db
sqlite> insert into main values ('carrier_services_enable_sensitive_logging', 'true');
```
