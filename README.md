---------------------------------------------------------------------------------------
 HackermanOS 
 ==============

An Android Custom ROM, That aims to provide Stability, Security & Speed. #HackermanOS : Developed with <3 by TechyMinati (Aryan Sinha)

Firstly you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

Firstly you need to initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/HackermanOS/android_manifest.git -b eleven

```

Then Sync The Source :

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compiling HackermanOS :
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch fusion_$device-userdebug
$ brunch <device_codename>
```
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**FusionOS**](https://github.com/FusionOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**RevengeOS**](https://github.com/RevengeOS)
 * [**POSP**](https://github.com/PotatoProject)
 * [**AOSiP**](https://github.com/AOSiP)
 * [**DotOS**](https://github.com/DotOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Havoc-OS**](https://github.com/Havoc-OS)
 * [**Xtended**](https://github.com/Project-Xtended)
 * [**OctaviOS**](https://github.com/Octavi-OS)
 * [**ColtOS**](https://github.com/Colt-Enigma)

