---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with Octavi-OS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/Octavi-OS/platform_manifest.git -b 12

```
or to save bandwith and space 

```bash
repo init -u https://github.com/Octavi-OS/platform_manifest.git -b 12 --depth=1
```

Then to sync up:

```
repo sync -c -f --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j8
```

---------------------------------------------------------------------------------------
 Compilation of OctaviOS:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch octavi_$device-userdebug
$ brunch <device_codename>
```

---------------------------------------------------------------------------------------

 More stuff :
 =======================
 
 * [**Bringup Guide for Octavi-OS**](https://github.com/Octavi-OS/Stuff)
 * [**XDA Thread**](https://github.com/Octavi-OS/xda)

---------------------------------------------------------------------------------------

### Links to official groups/channels
- [**Discussion Group**](https://t.me/OctaviOS_Chat)
- [**Announcements Channel**](https://t.me/octavi_os)
