manifest
========

The teamgelato Manifest

You'll need to 'repo init -u git://github.com/teamgelato/android.git -b cm-10.1'
and 'repo sync -j16'

. build/envsetup.sh

lunch cm_gelato-eng

cd vendor/cm && ./get-prebuilts && cd ../..

mka bacon
