B14CKB1RD-Kernel
-----------------------
The B14CKB1RD build envoronment that allows you to sync and build the kernel for multiple devices based on support


Initializing Repository
-----------------------

$ repo init -u https://github.com/B14CKB1RD-Kernel/kernel_manifests.git -b q


Sync Repository
---------------

$ repo sync


Building the kernel
--------------------
$ . build/envsetup.sh

$ lunch

$ make black
