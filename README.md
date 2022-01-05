KiCad AppImages
===============

These AppImages were built and tested on a Linux Mint 20. 

They were built using  https://github.com/AppImage/AppImages.git running  

## Building
To build an AppImage from a local `.yml` recipe (e.g., during development):

```
wget -c https://github.com/$(wget -q https://github.com/AppImage/pkg2appimage/releases -O - | grep "pkg2appimage-.*-x86_64.AppImage" | head -n 1 | cut -d '"' -f 2)
chmod +x ./pkg2appimage-*.AppImage
./pkg2appimage-*.AppImage recipes/kicad5.1-release.yml
```

## Launching

```
./KiCad-5.1.12.glibc2.29-x86_64.AppImage
```

for pcbnew standalone
```
./KiCad-5.1.12.glibc2.29-x86_64.AppImage pcbnew
```

for eeschema standalone
```
./KiCad-5.1.12.glibc2.29-x86_64.AppImage eeschema
```

or
```
./KiCad-6.0.0.glibc2.29-x86_64.AppImage
```


for pcbnew standalone
```
./KiCad-6.0.0.glibc2.29-x86_64.AppImage pcbnew
```

for eeschema standalone
```
./KiCad-6.0.0.glibc2.29-x86_64.AppImage eeschema
```

# Download
Please see [releases](https://github.com/KarlZeilhofer/kicad-appimage/releases) for all the binary AppImages for download (to be updated). 
