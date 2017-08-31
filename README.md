# cros-fw-manifests
Manifests for my coreboot build environment

1/ repo init with gru.xml(for gru firmware branch) or default.xml(for master branch):

$ repo init -u git@github.com:JeffyCN/cros-fw-manifests.git -m gru.xml -b master

2/ run repo sync to sync all codes

3/ run "./build.sh board" to build:

$ ./build.sh bob [options]


toolchains:

gcc-linaro-5.2-2015.11-1-x86_64_aarch64-linux-gnu.tar.xz  (for coreboot/payload/depthcharge/atf)

gcc-arm-none-eabi-4_9-2015q3-20150921-linux.tar.bz2  (for atf(m0)/ec)
