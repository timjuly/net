```
ln -s /home/ubuntu/projects/net/ubuntu/clash/clash.service /etc/systemd/system/clash.service
```

```
systemctl enable clash
systemctl start clash
```

```
journalctl -u clash
```

## Country.mmdb
https://cdn.jsdelivr.net/gh/Dreamacro/maxmind-geoip@release/Country.mmdb
