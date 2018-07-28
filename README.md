# andram

## Brief

The main purpose of this project is to maintain a script file named split_boot_img.py. Its a python script with version 2.

## Now Situation

It is not useful with python 3 bacause of the compatibility.

* Which has been migrate?

1. print function replacement

1. asc bytes decode to unicode for ensuring comparison pass

1. use int.from_bytes with sys.byteorder to fetch uint

1. force rstrip params using asc bytes (no use, remove them later)

* Break?

1. Base Address perhaps has some mistakes which need to be fixed.

## Credits

Thanks to [@vhernando](https://github.com/vhernando/split_boot_img)

Android Open Source Project
