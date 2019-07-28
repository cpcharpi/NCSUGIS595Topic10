# Topic 10: Writing and reproducing an open science paper #

## Assignment ##

Try to reproduce figures from the following paper:

https://doi.org/10.1186/s40965-017-0021-8
Report on how that went and how far did you get. Based on the last lecture, identify what may prevent others from reproducing the results of this paper and based on the whole class, identify what may prevent others from reusing methods and code presented in the paper. Consider how that may work in the future and consider also different potential audiences.

As you have surely noticed, there are no instructions here on how to reproduce the above paper. The paper itself gives instructions on how to do that. Hint: Don't read the whole paper, but look for the tools, platforms or any reproducibility-related information you would expect based on what you learned. More than one way of reproducing is provided, but one way is much simpler than the others.

## My Experience & Progress Report ##

Initially I struggled with getting docker to install to begin this assignment. It should be noted that I was attempting this in Mac OSX rather than in Linux Ubuntu. Eventually I folded and opted to work through the assignment with Linux rather than OSX. In Linux using a NCSU VCL reservation I was able to complete the entire exercise from installing Docker and running the docker file which ran through the GRASS GIS analysis to produce the output files and figures in the ffdata output folder. Based on my experience I would say the number one thing that may be a struggle for folks trying to reproduce the analysis from the paper is getting the Docker environment properly setup on a machine with GRASS GIS running. In addition, I could see how having limited system resources could be an issue for those working to mimic the results. A final note is that getting Docker setup in itself can be troublesome for those with limited experience.


### Output ###

This repository contains the output files and figures produced from running the dockerfile referenced in "Generalized 3D fragmentation index derived from lidar point clouds" paper. A repository from the paper at https://github.com/wenzeslaus/forestfrag3d was cloned to initiate docker.
