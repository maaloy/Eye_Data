# Eye_Data
Public Data of the PLOS ONE paper

The complete data-set employed to produce the paper has been uploaded in
a tar-gzipped file. The file is structured in several directories with
names that remind the different models in the paper. For instance,
"modelA" directory, contains the data associated to the model A in the
paper; "bobine"  directory, contains the data referring to the
complementary model made for a bobine eye; etc. Into each directory one
finds three kinds of data files, whose names have the following templates:

- dataT[a]M[b]P[c]B1_[NRxNT]_[number].dat: ASCII files that contain the
eigenvectors associated to a given model. The letters between square
brackets are variable and their meaning is:

[a] =number (1,2,3,...) This is simply to distinguish models (in case
they where in the same directory, since the data has been separated in
distinct subdirectories, they are not meaningful).

[b] = 4 or 5, to refer to "toroidal" or "radial" oscillatory modes.
[c] = 0, 1, 2. Identify variations of the radius of the eyeball.
[NRxNT] = 0100x0050 in all the files uploaded. Refers to the number of 
points in the radial and angular (theta) direction in which the eyeball
has been discretized.
[number] = integer number which identifies the eigenvalue to which the
eigenvector data file corresponds.

- eigvT[a]M[bP[c]]_[NRxNT].dat: ASCII files that contain the ordered
list of computed eigenvalues for each configuration. The letters between
square brackets have the same meaning as for the "data" files (above).

- files with extension ".gnu": these are gnuplot files which can be
directly used to read the data and produce figures of the eigenmodes.
They are provided for most subdirectories.
