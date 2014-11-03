utmech-soft3
============

ROS pkgs used in the class "Software3".


How to use this package in your catkin workspace
---
```bash
# clone this repo to the src directory in your catkin workspace
$ cd ~/catkin_ws/src
$ git clone https://github.com/utmech-2014/utmech-soft3.git

# make it
$ cd ..
$ catkin_make
$ catkin_make install
$ source ~/catkin/devel/setup.bash

# run samples
$ rosrun beginner_tutorials talker.py
$ rosrun keyop velocity.py
```

How to contribute to this repository
---
* First, fork this repository.
* Setup the git remote target in your local workspace.
```bash
$ cd ~/catkin_ws/src/utmech-soft3
$ git branch YOUR-GITHUB-USRNAME
$ git checkout YOUR-GITHUB-USRNAME
$ git remote add YOUR-GITHUB-USRNAME git@github.com:YOUR-GITHUB-USRNAME/utmech-soft3
```
* Change the sources in the branch and send pull requests!
