```bash
sudo cp 99-android.rules /etc/udev/rules.d/99-android.rules
sudo udevadm control --reload-rules
sudo systemctl restart systemd-udevd.service
```
