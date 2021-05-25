# futhark-stencil-benchmarks
This contains a number of benchmark program of stencils in futhark.

To run the benchmarks one can chose to use either the 
$ futhark bench
or use the makefile to 'make' in case that a GPU benchmarks are desired. It should be said that if one wishes to change the blocksize then this needs to be done in the makefile, as well as if one does not want to do GPU benchmarks.
