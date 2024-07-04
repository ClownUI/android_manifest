
![banner](https://raw.githubusercontent.com/ClownUI/android_manifest/vic/clown.png)
# ClownUI

## Getting Started ## 
---------------
To get started with the ClownUI sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/ClownUI/android_manifest.git -b vic --git-lfs
```

## Then sync up: ##

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build our source ###

```bash
. build/envsetup.sh
lunch clown_$devicecodename-ap3a-userdebug
make clown -j$(nproc --all) | tee log.txt
```

-----------------------------------------------------------------------------
Credits:
=======
<table border="5" cellpadding="10">
      <tr>
  		<td>
			<a href="https://android.googlesource.com"><img src="https://cdn1.iconfinder.com/data/icons/logotypes/32/android-512.png" width="100" alt="AOSP"></a>
		</td>
  <td><b>Android Open Source Project</b></td>
    <td>
			<a href="https://github.com/LineageOS">
				<img src="https://avatars.githubusercontent.com/u/24304779?s=200&v=4" width="100" alt="LineageOS"></a>
		</td>
  <td><b>LineageOS</b></td>
      <td>
			<a href="https://github.com/PixelOS-AOSP">
				<img src="https://avatars.githubusercontent.com/u/82160282?s=200&v=4" width="100" alt="PixelOS-AOSP"></a>
		</td>
  <td><b>PixelOS-AOSP</b></td>
      </tr>
  <tr>
    <td>
			<a href="https://github.com/GenesisOS"><img src="https://avatars.githubusercontent.com/u/137330039?s=200&v=4" width="100" alt="GenesisOS"></a>      
    </td>
    <td><b>GenesisOS</b></td>
    <td>
			<a href="https://github.com/AfterlifeOS"><img src="https://avatars.githubusercontent.com/u/128966441?s=200&v=4" width="100" alt="AfterlifeOS"></a>      
    </td>
    <td><b>AfterlifeOS</b></td>
    <td>
			<a href="https://github.com/ProjectInfinity-X"><img src="https://avatars.githubusercontent.com/u/153704129?s=200&v=4" width="100" alt="ProjectInfinity-X"></a>      
    </td>
    <td><b>ProjectInfinity-X</b></td>
  </tr>
    <tr>
    <td>
			<a href="https://github.com/ArrowOS"><img src="https://avatars.githubusercontent.com/u/40351870?s=200&v=4" width="100" alt="ArrowOS"></a>      
    </td>
    <td><b>ArrowOS</b></td>
    <td>
			<a href="https://github.com/xdroid-oss"><img src="https://avatars.githubusercontent.com/u/99038314?s=200&v=4" width="100" alt="Xdroid-OSS"></a>      
    </td>
    <td><b>Xdroid-OSS</b></td>
    <td>
			<a href="https://github.com/ancient-lab"><img src="https://avatars.githubusercontent.com/u/71782459?s=200&v=4" width="100" alt="AncientOS"></a>      
    </td>
    <td><b>AncientOS</b></td>
  </tr>
    <tr>
    <td>
			<a href="https://github.com/PixelExperience"><img src="https://avatars.githubusercontent.com/u/38539471?s=200&v=4" width="100" alt="PixelExperience"></a>      
    </td>
    <td><b>PixelExperience</b></td>
    <td>
			<a href="https://github.com/ProjectEverest"><img src="https://avatars.githubusercontent.com/u/155086159?s=200&v=4" width="100" alt="ProjectEverest"></a>      
    </td>
    <td><b>ProjectEverest</b></td>
    <td>
			<a href="https://github.com/DerpFest-AOSP"><img src="https://avatars.githubusercontent.com/u/71037289?s=200&v=4" width="100" alt="DerpFest-AOSP"></a>      
    </td>
    <td><b>DerpFest-AOSP</b></td>
  </tr>
    <tr>
    <td>
			<a href="https://github.com/RisingTechOSS"><img src="https://avatars.githubusercontent.com/u/121661057?s=200&v=4" width="100" alt="RisingTechOSS"></a>      
    </td>
    <td><b>RisingTechOSS</b></td>
    <td>
			<a href="https://github.com/Evolution-XYZ"><img src="https://avatars.githubusercontent.com/u/165590896?s=200&v=4" width="100" alt="Evolution-XYZ"></a>      
    </td>
    <td><b>Evolution-XYZ</b></td>
    <td>
			<a href="https://github.com/ProjectPixelage"><img src="https://avatars.githubusercontent.com/u/179228327?s=200&v=4" width="100" alt="Project Pixelage"></a>      
    </td>
    <td><b>Project Pixelage</b></td>
  </tr>
</table>
