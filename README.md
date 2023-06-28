## Wine prefixes for [Lutris Wine](https://github.com/VHSgunzo/lutris-wine)

## To create archlinux packages:
* **Download the latest revision**
```
git clone https://github.com/VHSgunzo/wine-prefix.git && cd wine-prefix
```

* **Create packages**
```
makepkg -fsCc --noconfirm --nodeps
makepkg -fsCc --noconfirm --nodeps -p PKGBUILD_dotnet
```
