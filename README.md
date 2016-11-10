# Solaris PCA Patching - ABE Reboot
Ansible Role for activating and rebooting into an ABE patched using role solaris-pca-patching

## Description

This role will activate and reboot into an ABE patched using solaris-pca-patching role.

The main cause for splitting roles is that ABE based patching is most useful to perform all work without impact and then activate the patched environment with the corresponding outage in a planned window, usually off hours for productions systems.
