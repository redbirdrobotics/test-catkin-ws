# `warning: libboost_system.so.1.58.0, needed by /opt/ros/kinetic/lib/libroscpp.so, may conflict with libboost_system.so.1.61.0`

solved with:
```sh
wget https://raw.githubusercontent.com/mavlink/mavros/master/mavros/scripts/install_geographiclib_datasets.sh
chmod +x install_geographiclib_datasets.sh # make sure we have permissions
./install_geographiclib_datasets.sh
```
