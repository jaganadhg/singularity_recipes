# Singularity Recipes
My Singularity Recipes for Data Science 

Singularity is a container solution for High Performance Computing and Scientific Computing Community. This repository is a collection of my recipes for various Machine Learning and Deep Learning excercises.

## Docker Based Images for Deep Learning (GPU)
All the recipes based on docker images (Ubuntu) included in the directory ubuntu_docker_nvidia.

## Build Centos/Fedora containers from Ubuntu/Debian
If we have to create Centos/Fedora containers from Ubuntu host;
1) Install yum 'sudo apt-get install yum'
2) Create a file '/root/.rpmmacros' .
Add the following content to the file
'
%_var /var
%_dbpath %{_var}/lib/rpm
'
Save and close the file. 

Now we can start building Centos/Fedora containers from Ubuntu


