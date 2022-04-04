# A-R-C-I-S
## UCF-SST Automated Roadway Conflicts Identify System (A.R.C.I.S)

This system, particularly applicable to road traffic analysis, uses drone/Unmanned Aerial Vehicle (UAV) videos. Video data from drones/UAVs are stabilized first, and then be processed through the automatic detection and tracking system based on state-of-the-art algorithms. This system also further corrects vehicles' tracking areas based on vehicles' moving conditions and detection results to provide more accurate outputs, especially for turning vehicles. Based on the detection and tracking results, the systems can generate the following types of outputs using drone/UAV video data:
- Trajectory data of road users including vehicles and vulnerable road users
- Road users' classifications
- Traffic statistics (e.g., volume, speed)
- Safety indicators (e.g., Post-Encroachment Time (P.E.T.))

The system can be applied for drone videos that are collected from different types of roadways, including freeway, arterial, and intersection.


#### ARCIS Merge Mutil-Drone video Demo
![droneMerge](https://github.com/ozheng1993/A-R-C-I-S/blob/master/asset/droneMerge.gif)

#### videoStabilizer Demo
![droneDemo](https://github.com/ozheng1993/videoStabilizer/blob/master/assets/demo.gif)

## Requirements

Python 3.6+, pysimplegui,opencv-python and other common packages listed in `requirements.txt`.

## Installation

1. Clone this repository
2. Install dependencies
   ```bash
   pip3 install -r requirements.txt
   ```
3. Run setup from the repository root directory
    ```bash
    python3 setup.py install
    ``` 
## Getting Started

1. Start 

## Interface

## To do

* userinterface

## Contributing
Contributions to this repository are welcome. Examples of things you can contribute:
-TBD
## please email:M.Aty@ucf.edu for demo

## Citation
      @article{zheng2019developing,
        title={Developing a Traffic Safety Diagnostics System for Unmanned Aerial Vehicles UsingDeep Learning Algorithms},
        author={Zheng, Ou},
        year={2019},
        publisher={University of Central Florida}
      }

