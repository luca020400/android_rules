```bash
sudo cp 50-android.rules /etc/udev/rules.d/
sudo udevadm control --reload-rules
sudo systemctl restart systemd-udevd.service
```
