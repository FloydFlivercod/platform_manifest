[Floyd Flivercod Bare Bones ROM](Based from GZOSP)
====================================


Download the Source
===================

Repo initialization:

    $ repo init -u https://github.com/FloydFlivercod/platform_manifest.git -b p9.0


sync repo :

    $ repo sync --force-sync

Smallest/fastest sync:

    $ repo sync --no-tags --no-clone-bundle

    . build/envsetup.sh
    brunch


You can also build (and see how long it took) for specific devices like this:

    . build/envsetup.sh
    time brunch oneplus3 

Remember to `make clobber` every now and then!

Kudos, love mail, hate mail & go to hells all welcome... I'm a one man Hacker on a mission for myself ;)
