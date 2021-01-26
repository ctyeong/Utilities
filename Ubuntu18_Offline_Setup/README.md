# Ubuntu18 Offline Setup 

This is for an issue that I have faced with a computer in which Ubuntu 18 was newly installed. 

**Issue:** Computer has to stay offline because Ubuntu cannot install any appropriate network driver for that particular machine. Furthermore, the network drivers, downloaded from another online computer, require essential Linux packages for compilation and installation.

**Remedy:** 
1. Using another computer `B` that can access online, download the files uploaded here, which are `.deb`'s to install `build-essential` and `dkms` with all necessary dependent packages. 
2. Copy and paste to the offline machine `A`, and run `$ sudo dpkg -i *.deb` in the directory of the files. 
3. Find proper drivers from online in `B` and install them on `A` to be able to eventually connect to the internet.

**What's happening:**
- Following the instruction [here](https://ivanitlearning.wordpress.com/2019/04/21/installing-ubuntu-packages-and-git-repos-offline/), those `.deb`'s have been downloaded in a pure Ubuntu machine with internet connection. 
