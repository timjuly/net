参见：https://emby-keeper.github.io#安装与使用

```
python -m venv embykeeper-venv
. ./embykeeper-venv/bin/activate
pip install embykeeper
```

```
ln -s /home/ubuntu/projects/net/ubuntu/embykeeper/embykeeper.service /etc/systemd/system/embykeeper.service
```

```
systemctl enable embykeeper
systemctl start embykeeper
```

```
journalctl -u embykeeper
```
