This repo contains the yocto setup needed to build image for Haridwar board bring up.


##Logs received from bitbake-build setup

Setting up bitbake configuration in
    /home/kshitij/src/haridwar_bsp/bitbake-builds/poky-wrynose/build

This bitbake configuration provides:
    Poky - The Yocto Project testing distribution

Usage instructions and additional information are in
     /home/kshitij/src/haridwar_bsp/bitbake-builds/poky-wrynose/build/README

To run builds, source the environment using
    . /home/kshitij/src/haridwar_bsp/bitbake-builds/poky-wrynose/build/init-build-env

Run 'bitbake-config-build enable-fragment <fragment-name>' to enable additional fragments or replace built-in ones (e.g. machine/<name> or distro/<name> to change MACHINE or DISTRO).

The bitbake configuration files (local.conf, bblayers.conf and more) can be found in
    /home/kshitij/src/haridwar_bsp/bitbake-builds/poky-wrynose/build/conf

To edit the code in VSCode, open the workspace:
    code /home/kshitij/src/haridwar_bsp/bitbake-builds/poky-wrynose/bitbake.code-workspace