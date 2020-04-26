# live-build configuration for Kali ISO images

Setup steps:
```
sudo apt install -y curl git live-build cdebootstrap
git clone https://github.com/Johan-p/Custom-Kali-ISO.git
cd Custom-Kali-ISO/
./build.sh --verbose
```

To add or remove packages in your own ISO edit the default file or create your own version:
```
Custom-Kali-ISO/kali-config/variant-xfce/package-lists/kali.list.chroot
```

Selecting packages/tools:
https://tools.kali.org/kali-metapackages


Have a look at https://docs.kali.org/development/live-build-a-custom-kali-iso
for explanations on how to use this repository.
