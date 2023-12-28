# Ubuntu Touch Adaptation Tree for Daria Bond 5G
Device Codename: zahedan 
Device Manufacturer: Daria
Chipset: Mediatek Dimensity 7050 (MT6877) 
Based on: Halium 12

## How To Build:
#### Setup Build Environment:
use ubuntu machine (docker, vm, host, etc.)  and Install needed packages:

    sudo apt install android-tools-mkbootimg bc bison build-essential \
    ca-certificates cpio curl flex git kmod libssl-dev libtinfo5 python2 \
    sudo unzip wget xz-utils img2simg jq

Clone this Repo:

    git clone https://github.com/shayan53/ubports-zahedan.git

#### Now you can simply build the ubuntu touch by running the following command:

    cd ubports-zahedan
    ./build.sh -b dest

