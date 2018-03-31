# Vehicle Localization Using Particle Filters
In this project, we will implement a 2-dimensional particle filter in C++. The particle filter will be given a map and some initial localization information (analogous to what a GPS would provide) to localize a vehicle.

## Running the Code
This project involves the Udacity's Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases)

This repository includes two files that can be used to set up and intall uWebSocketIO for either Linux or Mac systems.

Once the install for uWebSocketIO is complete, the main program can be built and ran by doing the following from the project top directory.

1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./particle_filter

Alternatively some scripts have been included to streamline this process, these can be leveraged by executing the following in the top directory of the project:

1. ./clean.sh
2. ./build.sh
3. ./run.sh

After running the particle_filter, open the simulator and select the project, then press start.
The simulator will run the code in `particle_filter.cpp` and then prints the following if succeeded to run within 100 seconds:
```
Success! Your particle filter passed!
```

The directory structure of this repository is as follows:
```
root
|   build.sh
|   clean.sh
|   CMakeLists.txt
|   README.md
|   run.sh
|
|___data
|   |   
|   |   map_data.txt
|   
|   
|___src
    |   helper_functions.h
    |   main.cpp
    |   map.h
    |   particle_filter.cpp
    |   particle_filter.h
```
