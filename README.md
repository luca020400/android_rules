https://github.com/systemd/systemd/commit/edc49209f175c354bc4055281a377a4e9dc21e6c

```bash
sudo cp 50-android.rules /etc/udev/rules.d/
sudo udevadm control --reload-rules
sudo systemctl restart systemd-udevd.service
```
