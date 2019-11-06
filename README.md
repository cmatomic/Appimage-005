# VLCplayer-AppImage-SNAP
#### This is experimental appimage
Unofficial VLCplayer AppImage, VLC version import from SNAPS repository

## Download
Download the AppImage from [here](https://github.com/cmatomic/VLCplayer-AppImage-SNAP/releases).


## build your own version

The script will import VLCplayer from the snap repository and convert it to an Appimage
The following sequence of commands will download the necessary files and execute them to generate the VLC player appimage, then you can access the VLCscript / out folder and click on the VLC appimage.
In some distros it is necessary to install  "wget" "fuse" "APT" "appstream" "gcc" , these scripts will work on debian based distros .

* ### VLC player stable version
```
mkdir VLCscript;cd VLCscript;wget https://raw.githubusercontent.com/cmatomic/RecipesAppimage/master/VLCplayerSnap/VlcPlayerSnap.sh;chmod +x Vlc*.sh;./Vlc*.sh
```

* ### VLC player beta 
```
mkdir VLCscript;cd VLCscript;wget https://raw.githubusercontent.com/cmatomic/RecipesAppimage/master/VLCplayerSnap/VlcPlayerBetaSnap.sh;chmod +x Vlc*.sh;./Vlc*.sh
```

* ### VLC player Edge
```
 mkdir VLCscript;cd VLCscript;wget https://raw.githubusercontent.com/cmatomic/RecipesAppimage/master/VLCplayerSnap/VlcPlayervlcEdgeSnap.sh;chmod +x Vlc*.sh;./Vlc*.sh  
```

## VLC version build from source
If you are looking for a stable version Download the AppImage from [here](https://github.com/cmatomic/VLCplayer-AppImage/releases).
