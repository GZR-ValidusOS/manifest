<img src="https://raw.githubusercontent.com/HassanSardar/manifest/Redesign/Validus_Banner.png">

The GZR Validus OS Project - Nougat 7.1.2
========

To get started with Android, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the ValidusOS trees, use a command like this:
-----------------------------------------

	repo init -u https://github.com/GZR-ValidusOS/manifest.git -b n7.1.2


Then to sync up:
-----------------------------------------

    repo sync -c --force-broken --force-sync --no-clone-bundle --no-tags
    
When The Repo Is Synced, Type:
-----------------------------------------
```
. build/envsetup.sh
lunch
Choose your device
```
Device Lunched? No? Repeat. Yes? What's The Wait? Type:
-----------------------------------------------------
```
mka validus
```
Have Fun Building Your Validus!
-----------------------
