参见：https://emby-keeper.github.io#安装与使用

```
python3 -m venv embykeeper-venv
. ./embykeeper-venv/bin/activate
pip install embykeeper -i https://pypi.org/simple
```

```
ln -s /home/ubuntu/projects/net/ubuntu/embykeeper/embykeeper.service /etc/systemd/system/embykeeper.service
```

```
sudo systemctl enable embykeeper
sudo systemctl start embykeeper
```

```
journalctl -u embykeeper
```
