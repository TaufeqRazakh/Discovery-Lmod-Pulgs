# Modules for USCCACS Projects

## Purpose
> All we want is to carry out scientific exploration, atleast when we ssh.

The CACS Lab @ USC is actively developing codes to do material simulation at multiple scale and also maintain it's code in production at the targeted leadership supercomputing machines as well as our home research clusters. This repository is dedicated to ensuring the most relevant tools to development are available on (USC's Center for Advanced Research Computing)[https://www.carc.usc.edu]'s Discovery cluster. Practically speaking, members of the group are nearly daily engaged in scientific discovery, and to make the missing tools available to all members, we build and placed them in the common `project/` directory. Why? Because these tools can be loaded as modules.
This repository houses a collection of lua scripts that will play well with the existing module system. So if you are from CACS and reading this, all you need to do is use our modulefiles in addition to the ones available on CARC and not ever have to deal with setting any PATH/environment variable and wonder, has it linked?

## How to use and load
To use any of the available modules, first add them to your default module path with the following command.
```
module use /project/anakano_81/razakh/linux-centos7-x86_64/lmod/
```
From here you should be able to see all the available modules with the command `module avail` and load the packages you need with the `module load <PackageName>` command. For instance if you want use llvm/15.0.0 which is made available you, use the familiar command as follows.
```
module load llvm/15.0.0
```

## Happy Computing
