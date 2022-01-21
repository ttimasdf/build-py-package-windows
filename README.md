# build-py-package-windows

Build **ANY** python (especially Cython) package wheel for **ANY** python version for windows, without need to install Windows SDK locally at all!

What exactly do we need for compiling pyx codes in Windows? From what I test, the 6 packages below are the minimum and mandatory dependency, occupying **6.04 GB** of disk space.

![image](https://user-images.githubusercontent.com/2762704/150496300-75b3e5ad-dec9-47ce-885f-7458b17b484f.png)

With Github Actions, we could get out of this bloatware once and for all.

# Usage

Just fork this repo and edit the yml file, change the package name and install dependencies if necessary. After commited, check the Actions tab and find the artifact.
