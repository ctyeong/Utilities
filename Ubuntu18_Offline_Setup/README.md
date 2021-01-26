# Ubuntu18 Offline Setup 

This is for an issue that I have faced with a computer in which Ubuntu 18 was newly installed. 

**Issue:** Computer has to stay offline because Ubuntu cannot install any appropriate network driver for that particular machine. Furthermore, the network drivers, downloaded from another online computer, require essential Linux packages for installation.

**Remedy:** 
1. Download the files uploaded here, which are `.deb`'s to install `build-essential` and `dkms` with all necessary dependent packages. 
2. Run `$ sudo dpkg -i *.deb` in the directory of the files. 

**What's happening:**
- Following the instruction [here](https://ivanitlearning.wordpress.com/2019/04/21/installing-ubuntu-packages-and-git-repos-offline/), those `.deb`'s have been downloaded in the pure Ubuntu machine with internet connection. 