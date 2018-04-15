# any issues?
try opening a new terminal any sourcing the environment variables again (from a 
properly built catkin workspace) using `source devel/setup.bash`.

Gain an ssh into vehicle computer and execute the following commands:

```sh
git clone https://github.com/redbirdrobotics/test-catkin-ws
cd test-catkin-ws
catkin build
source devel/setup.bash
roslaunch redbird_m7a_vehicle startup.launch
rosservice call /redbird/flight_director/start_flight "takeoff_land"
```

