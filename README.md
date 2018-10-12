razer_hydra
===============

ROS package for razer hydra motion controller. 
This is an unofficial driver which does NOT use the official Sixense SDK.

See documentation on the ros wiki: http://www.ros.org/wiki/razer_hydra


## Installation
- use `catkin_make` for compilation

- copy the `99-hydra.rules` file to `/etc/udev/rules.d`
```bash
roscd razer_hydra
sudo cp config/99-hydra.rules /etc/udev/rules.d
```


- restart udev service
```bash
sudo service udev restart
```
