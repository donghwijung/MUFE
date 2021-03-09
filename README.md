# MUFE: Multi-Floor Mapping including the Elevator
Donghwi Jung, Heungmin Park, Jinwoo Lee, Kyunghyun Kim, Giulia Nespoli, and Seong-Woo Kim, "MUFE: Multi-Floor Mapping including the Elevator," submitted to IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Prague, Czech Republic, 2021.
## Dataset
The link for dataset is https://drive.google.com/drive/folders/189B0eBK0MVQ9wGlaF7IceNS17MB1W0zq?usp=sharing
```
/velydone_points 10 Hz, Velodyne VLP 16
/imu/data 400 Hz, Xsens 680G
/pressure 25 Hz, BMP 180
```
Data description
* The dataset was collected in building 3.
* The ground truth floor-to-floor height for building 3 is 4.16 m.
* 'bld3_5th_to_3rd' includes a journey starting on the 5th floor, going through the 3rd floor and back to the 5th floor.
* 'bld3_3rd_to_4th_to_5th_round' is a path that goes back and forth over three floors. The detailed transitions are as follows: 3->4->5->3->4F.
* 'bld3_5th_to_1st_elv' is the route from the 5th floor to the 1st floor by elevator.

## Video
https://youtu.be/S_8OZRwpDY4