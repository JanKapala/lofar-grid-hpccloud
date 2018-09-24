# lofar-grid-hpccloud
Visit the  [wiki](https://github.com/tikk3r/lofar-grid-hpccloud/wiki) for more detailed information.
----------------------------------------
This repository hold resources for deploying the LOFAR software and related tools through Singularity images.
 
 
Other software related notes
----------------------------
- Python CASAcore `setup.py` is broken with regards to finding libraries passed along by the -L flag. This is fixed with the patch.
- Latest log4cplus requires CMake 3.6:

    yum install -y cmake3
    
- Installing log4cplus requires `--recursive` when cloning, otherwise the `catch.hpp` and `threadpool.h` headers are not found.

    
