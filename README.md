# live-build configuration for Gnoppix ISO images

Example: 

./build.sh --verbose --arch i386

This will build you for older i386 architecture


./build.sh --variant kde --verbose 
build a KDE ISO


./build.sh --variant kde --arch i386 --verbose
build a KDE ISO for the older i386 architecture


Variants: 

variant-gnome
variant-light		
variant-xfce
variant-i3wm
variant-lxde
variant-e17
variant-kde
variant-mate
netinst	
everything			
variant-minimal

teoretically you can build on all 23 different architecures listed here: 

https://wiki.debian.org/SupportedArchitectures

Credits: 
This was originally forked from Debian https://salsa.debian.org/public

