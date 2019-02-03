H4K3ROM [LineageOS Source]
===========


```
Follow build steps for LineageOS

mkdir H4K3ROM && cd H4K3ROM

repo init -u git://github.com/H4K3ROM/android.git -b lineage-16.0

then do:
repo sync --force-sync && . build/envsetup.sh && . vendor/lineage/h4k3rom.sh && brunch oneplus3

