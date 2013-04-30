mtd-utils-am335x
================

mtd-utils used for am335x for large 4KiB page with 224 oob 


pre
===
We need install this before compilation:

    apt-get install zlib1g-dev liblzo2-2 liblzo2-dev uuid-dev


make
====
     
    cd mtd-utils-am335x
    make WITHOUT_XATTR=1


Ref
===
http://processors.wiki.ti.com/index.php/MTD_Utilities#MTD-Utils_User-space_tools
