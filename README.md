# caesar_base
Singularity base container for CAESAR

This repository provides the recipe file to build the base container for CAESAR tool (maintained at https://github.com/simoneriggi/ska.git). The built container will provide all dependencies needed to build CAESAR:

- ROOT
- OpenCV
- BOOST
- Log4Cxx
- Jsoncpp
- cfitsio
- protobuf
- MPICH
- OpenMPI
- python 2.7 + modules (numpy, astropy, pyfits)
	
The container is used mainly to build CAESAR upon it.
