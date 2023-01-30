```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jspricke/autoware-deb-packages/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_autoware-deb-packages.list
echo "yaml https://raw.githubusercontent.com/jspricke/autoware-deb-packages/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_autoware-deb-packages.list
```
