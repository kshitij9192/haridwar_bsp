This repo contains the yocto setup needed to build image for Haridwar board bring up.

#To invoke initial setup
./bitbake/bin/bitbake-setup init --non-interactive base.conf.json haridwarconf kkdistro machine/haridwar-board

To run builds, source the environment using
    . /home/kshitij/tools/lnx/haridwar_bsp/bitbake-builds/base-haridwarconf/build/init-build-env

Run 'bitbake-config-build enable-fragment <fragment-name>' to enable additional fragments or replace built-in ones (e.g. machine/<name> or distro/<name> to change MACHINE or DISTRO).

The bitbake configuration files (local.conf, bblayers.conf and more) can be found in
    /home/kshitij/tools/lnx/haridwar_bsp/bitbake-builds/base-haridwarconf/build/conf
