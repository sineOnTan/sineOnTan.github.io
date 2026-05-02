# Introduction

Hit detection is a key element of video games and needs to be optimised to ensure the efficient calculation of data in a low latency environment. This is a short investigation into how these work and various optimisation that are used. All code used here has not been tested and is mainly research or concept material.

# Background

Valorant hitboxes are represented as pills, a line with a radius spanning around it. For this one we will only look at bullets (represented as lines) and how they are calculated for a hit.<br>

Based on this [video](https://youtu.be/01OJ5SYLeGQ?t=335) there are about 17 hitboxes per agent.

# Cameras/Bullets

Firstly, we need to establish how camera/bullet direction is calculated. Typically this is stored as yaw (horizontal) and pitch (vertical) for the camera angle. This helps establish where a person is looking. One example is CS2/GO.

[Example code](https://github.com/sineOnTan/HitDetection/blob/main/yawPitch.cpp)

# Spatial Partition

Spatial Partitions are used to break the map into smaller more manageable areas.

The following code gets a line and calculates the next box a line will enter.
To ensure you do not indefinitely calculate bounding boxes there is a world box limit. (This is an assumption based on the fact it would be impossible to stop a line if there was not which would be computationally expensive)

[Example code](https://github.com/sineOnTan/HitDetection/blob/main/spatialPartition.cpp)<br>
[3D partition example](https://github.com/sineOnTan/HitDetection/blob/main/3DspatialPartition.cpp)

# Bounding Boxes

Bounding boxes are typically axis aligned and can help optimisations by providing simple calculations on whether a line can possibly intercept more complex hitboxes or polygons. So rather then calculate 10 hitboxes, we calculate 1 larger one first to ensure it is possible for the smaller ones to be reachable. There is a variety of ways of this being stored however a possible way is storing x,y,z coords and their lengths.

[Example code](https://github.com/sineOnTan/HitDetection/blob/main/boundingBoxes.cpp)

## Bounding Box collision

test

