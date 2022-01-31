# flatpak-builder
```
git clone https://github.com/JayDoubleu/terminator.git --branch flatpak_flathub_manifest --single-branch --recurse-submodules -j8
cd terminator/experimental/flatpak
flatpak install org.gnome.Sdk//41
flatpak-builder --user --install --force-clean build-dir net.tenshu.Terminator2.yml
flatpak run net.tenshu.Terminator2
```
