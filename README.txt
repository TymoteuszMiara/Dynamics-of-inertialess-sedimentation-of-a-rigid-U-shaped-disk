The larger disk's geometry can be found in "LargerDiskSurface.dat" file (this file is normalised by radius which in these experiments was 12mm).
The smaller disk's geometry can be found in "SmallerDiskSurface.dat" file (also normalised by radius which in this case was 5mm).

All of the "*Experiment*.dat" files have the following format:
Each row corresponds to one data point at a given instant in time.
The first column is time
Columns 2-4 are the (x,y,z) of the position of the centre of mass. The centre of the coordinate system is at the centre of the tank at the top of the surface of the liquid. 
Columns 5-7 are the (x,y,z) components of the x_1 vector (roll axis)
Columns 8-10 are the (x,y,z) components of the x_2 vector (pitch axis)
Cloumns 11-13 are the (x,y,z) components of the x_3 vector (normal vector)
The remaining 144 columns represent a 12x12 covariance matrix of the values in columns 2-13. 

