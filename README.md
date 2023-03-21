This is a collection of patches to run VirtualBox 5.2.44 on newer host linux systems than it was officially intended for.

* Backport of compatability updates for host linux kernels up to 5.18
* Backport of various small VMM fixes
* Backport of Qt compatability fixes
* Various other usefull patches
* A compatability patch for linux kernel to avoid invasive modification of VMM ring 0 images (optional).

Note1: vbox patches are to be applied in alphabetical order, some of them
(e.g. all of suse patches) might be skipped as necessary.

Note2: linux kernel patch is only required unless the "no-vm_area" vbox patch is applied 

HTH! :-)
