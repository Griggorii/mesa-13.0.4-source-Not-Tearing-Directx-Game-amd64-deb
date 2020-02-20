# mesa-13.0.4-source-Not-Tearing-Directx-Game-amd64-deb
deb , mesa , source , 13.0.4 , Not , Tearing , Directx9 , Directx11 , window , amd64 , debian , ubuntu

llvm-9.0.1_1-1_amd64.deb https://drive.google.com/open?id=1COizcVRsss84l_tLQdxzu2LMFM1J8i_v replace llvm standart

sudo dpkg -i llvm-9.0.1_1-1_amd64.deb

Run in folder terminal mesa-13.0.4

./configure --prefix=/usr --exec-prefix=/usr/lib/x86_64-linux-gnu/ --enable-glx-tls --enable-driglx-direct --enable-xa --enable-texture-float --enable-osmesa --enable-gles1 --enable-gles2 --enable-opencl-icd --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-gallium-drivers=r300,r600,radeonsi,svga,swrast --enable-autotools --with-gallium-drivers=r600 --disable-gallium-llvm --enable-sysfs --with-egl-platforms="drm,x11"

make -j16

sudo make install

Установите это ядро что бы внутри игр при вызове внутренне игрового гуя в wine именно в directx звук не заикался вместе с изображением https://github.com/Griggorii/linux-image-zfs-4.4.201_4.4.201-3_amd64 либо установите ядра от xenial список ниже

linux-headers-4.4.0-116_4.4.0-116.140_all.deb

linux-headers-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-extra-4.4.0-116-generic_4.4.0-116.140_amd64.deb

---------------------------------------------------------------------

Установка именно готового пакета

sudo dpkg -i mesa_13.0.4-1_amd64.deb

Replace | заменяет mesa , libegl1-mesa-dev , mesa-common-dev , libgles2-mesa-dev , libosmesa6-dev , libgl1-mesa-dri:amd64 , libgl1-mesa-dri:i386 , libgbm-dev:amd64 , libegl1-mesa-dev

Состоит в таких группах video , games , users , kvm , voice , colord , pulse , pulse-access , bluetooth , rdma , irc , playonlinux , wine

Uninstall mesa_13.0.4 synaptic find griggorii@gmail.com update install reinstall mesa standart repository mesa

