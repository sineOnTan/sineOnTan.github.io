# Introduction

Hit detection is a key element of video games and needs to be optimised to ensure the efficient calculation of data in a low latency environment. This is a short investigation into how these work and various optimisation that could be used.

# Background

Valorant hitboxes are represented as pills, a line with a radius spanning around it. For this one we will only look at bullets (represented as lines) and how they are calculated for a hit.<br>

Based on this [video](https://youtu.be/01OJ5SYLeGQ?t=335) there are about 17 hitboxes per agent.

# Cameras/Bullets

Firstly, we need to establish how camera/bullet direction is calculated. Typically this is stored as yaw (horizontal) and pitch (vertical) for the camera angle. This helps establish where a person is looking.

# Bounding Boxes

Bounding Volumes are used to break the map into smaller more manageable areas. Typically these are cubes or spheres. In the case of Valorant these are cubes (based on online sources).
