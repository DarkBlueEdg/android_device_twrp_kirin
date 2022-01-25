# Sony Xperia 10 Dual Sim I4113 Kirin

For prebuilt get TWRP.img
-------------------------
```
abootimg -x TWRP.img
```

```
mv initrd.img initrd.gz
```

```
gunzip initrd.gz
```

```
mkdir tmp
```

```
cd tmp
```

```
cpio -m -i <../initrd
```

```
zip -ry ../ramdisk-recovery.zip *
```
