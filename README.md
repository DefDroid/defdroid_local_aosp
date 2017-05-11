defdroid_local_aosp
========================

Local manifests for DefDroid based on AOSP tree 

Getting Started
---------------
This is currently only intended to be used by project members of DefDroid as
the manifest file refers to project repositories that are currently hosted 
as private.

Follow the standard way of getting a [AOSP source tree](https://source.android.com/source/downloading)
with the branch that matches the DefDroid release version, e.g., **android-5.1.1_r3**.
Then switch to the root of the source tree and checkout this repository to 
`.repo/local_manifests`. Then sync up with
```
repo sync
```
