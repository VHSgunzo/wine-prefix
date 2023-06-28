## Wine prefixes for [Lutris Wine](https://github.com/VHSgunzo/lutris-wine)

## To create archlinux packages:
* **Download the latest revision**
```
git clone https://github.com/VHSgunzo/wine-prefix.git && cd wine-prefix
```

* **Get prefix backup files from the** [releases](https://github.com/VHSgunzo/wine-prefix/releases)

* **Create packages**
```
makepkg -fsCc --noconfirm --nodeps
makepkg -fsCc --noconfirm --nodeps -p PKGBUILD_dotnet
```
