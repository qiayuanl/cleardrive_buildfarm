```bash
echo "deb [trusted=yes] https://github.com/qiayuanl/cleardrive_buildfarm/raw/focal-noetic-amd64/ ./" | sudo tee /etc/apt/sources.list.d/qiayuanl_cleardrive_buildfarm.list
echo "yaml https://github.com/qiayuanl/cleardrive_buildfarm/raw/focal-noetic-amd64/local.yaml noetic" | sudo tee /etc/ros/rosdep/sources.list.d/1-qiayuanl_cleardrive_buildfarm.list
```
