# CItcomS_more_than_2tracers_using_ggrd
Previous CitcomS ggrd version can handle 2 tracers at a time, this new modification can handle more than 2 tracers using grd file handling.

If you are willing to dwoanload this version, please email me (debanjanpal@iisc.ac.in).

While Installing this version it is recomended to create your own configure file using the command autoreconf -ifv
Also please exceute this command "make clean" before installing once.

If you wish to give different buoyancy for different tracer flavors replace the new Composition_related.c file that has been newly added seperately with the one that is inside the library file
