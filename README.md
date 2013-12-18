Submitting Patches
------------------
We're open source, and patches are always welcome!
You can send us pull requests.

Getting Started
---------------

To get started with Ampere Rom, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the Ampere trees, use a command like this:

    repo init -u git://https://github.com/AmperificSuperKANG/android.git -b <branch>

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>