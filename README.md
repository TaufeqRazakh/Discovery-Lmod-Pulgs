# Modules for USCCACS Projects

## Purpose
> All we want is to carry out scientific exploration, atleast when we ssh.

The CACS Lab @ USC is actively developing codes to do material simulation at every scale and also maintain it's code in production at top supercomputers and leading research clusters. This repository is dedicated to ensuring the most relevant tools to development are available on (USC's Center for Advanced Research Computing)[https://www.carc.usc.edu]'s Discovery cluster. Practically members of the group engage in scientific discovery and to make latest tools available to all members, necessary tools are built and placed in the common `project/` directory. These tools can be loaded as modules. This is a collection of the lua scripts that will play well with the existing module system. So if you are from CACS and reading this, all you need to do is use our modulefiles in addition to the ones available on CARC and forget about setting the PATH or any other environment variables that the tool requires.

## How to use and load
To use any of the available modules, first add them to your default module path with the following command.
```
module use /project/anakano_81/razakh/linux-centos7-x86_64/lmod/
```
From here you should be able to see all the available modules with the command `module avail` and load the packages you need with the `module load <PackageName>` command. For instance if you want to you llvm/15.0.0 which we make available you would now use the familiar command.
```
module load llvm/15.0.0
```

## Happy Computing
