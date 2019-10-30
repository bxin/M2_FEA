The final bending mode forces based on the finite element model as
delivered by Harris
\url{https://github.com/bxin/M2_FEA/blob/master/data/M2_1um_72_force.txt}.
Each row is for an actuator. There are 72 rows in total.
The first column is the actuator ID. The 2nd and 3rd columns are the x
and y coordinates of the actuators in meter. The rest of the columns are forces
for individual bending modes in Newton.
The bending mode shapes are at
\url{https://github.com/bxin/M2_FEA/blob/master/data/M2_1um_72_grid.txt}
Each row is for a surface node. There are 15984 rows in total. The
first column is the node ID. The 2nd and 3rd columns are the x and y
coordinates in meter for that node. The rest of the columns are for
individual bending modes. Note that these are surface normal
displacements in meter, which need to be projected to surface sag if
used in raytrace programs.
The surface sag bending modes are at
\url{https://github.com/bxin/M2_FEA/blob/master/data/M2_1um_72_sag.txt}
This follows the same format as the surface normal modes.
