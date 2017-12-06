
# Install CUDA Drivers
://developer.nvidia.com/cuda-downloads?target_os=Linux&target_arch=x86_64&target_distro=Ubuntu&target_version=1604&target_type=debnetwork

# Choose OS: Linux
# Architecture: x86_64
# Distro: Ubuntu
# Version: 16.04
# Installer Type: deb(network)
# Follow Instlal Instructions

# Configure Nvidia Xconfig
nvidia-xconfig --enable-all-gpus --separate-x-screens --allow-empty-initial-configuration


# Download and install ccminer
https://github.com/tpruvot/ccminer/blob/linux/INSTALL
./build.sh
./autogen.sh
./configure
# Install dependencies
sudo apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential

sudo apt-get install gcc-5 g++-5
./build.sh
./ccminer --version
