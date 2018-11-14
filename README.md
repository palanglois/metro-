### Splitted metro distance ###

Samples n points on mesh_1 and mesh_2. Computes the nearest neighbour distance between each point of 
mesh_1 to all_points of mesh_2 and the other way around.

If mesh_1 is a ground truth and mesh_2 is an experiment, the first given value is the precision ; the 
second value is the completeness

* All dependencies included, build with CMake
* Example : `./metro_pp mesh_1.ply mesh_2.ply 100000` where the last argument is the number of 
points sampled on each mesh.
