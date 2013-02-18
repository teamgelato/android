manifest
========

The teamgelato Manifest

Here's a rough guide to building CM 10.1 for the vm701 -

You'll need to fetch the androidarmv6 cm 10.1 repo at github.com/androidarmv6/android branch cm-10.1

Download this local_manifest.xml and place it in .repo

As of now this repo still goes of p690 paths so build for the p690

. build/envsetup.sh

lunch cm_p690-eng

cd vendor/cm && ./get-prebuilts && cd ../..

mka bacon
