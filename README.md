# mesa-13.0.4-source-Not-Tearing-Directx-Game-amd64-deb
deb , mesa , source , 13.0.4 , Not , Tearing , Directx9 , Directx11 , window , amd64 , debian , ubuntu

llvm-9.0.1_1-1_amd64.deb https://drive.google.com/open?id=1COizcVRsss84l_tLQdxzu2LMFM1J8i_v replace llvm standart

sudo dpkg -i llvm-9.0.1_1-1_amd64.deb

Download folder tizonia https://github.com/Griggorii/mesa-19.0.1_source_griggorii_mit_patent_llvm-7 tizonia run in folder terminal command $$ sudo dpkg -i *.deb && sudo apt update -y && sudo apt install -f -y

sudo rm - rf /etc/X11/xorg.conf 

sudo rm - rf /etc/X11/xorg.conf.failsafe 

sudo rm - rf /usr/share/X11/xorg.conf.d/20-nouveau.conf 

sudo rm - rf /usr/share/X11/xorg.conf.d/20-intel.conf

sudo apt update && sudo apt install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt libmesa-dev -y && sudo apt install libd3dadapter9-mesa-dev -y


Run in folder terminal mesa-13.0.4

./configure --prefix=/usr --exec-prefix=/usr/lib/x86_64-linux-gnu/ --enable-glx-tls --enable-driglx-direct --enable-xa --enable-texture-float --enable-osmesa --enable-gles1 --enable-gles2 --enable-opencl-icd --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-gallium-drivers=r300,r600,radeonsi,svga,swrast --enable-autotools --with-gallium-drivers=r600 --disable-gallium-llvm --enable-sysfs --with-egl-platforms="drm,x11"

make -j16

sudo make install

Установите это ядро что бы внутри игр при вызове внутренне игрового гуя в wine именно в directx звук не заикался вместе с изображением https://github.com/Griggorii/linux-image-zfs-4.4.201_4.4.201-3_amd64 либо установите ядра от xenial список ниже но в xenial возможно не будет поддержки ubuntu 19.04 и 19.10 потому что это ядро не собиралось в той среде где папки в корне стали ссылками начиная с 19.04 /lib /lib64 тоже ссылкой после установки обязательно удалите ссылки на initr и другие которые появятся в корне / потому что ядра должны быть в boot и без всяких ссылок в корне фактически потом эти линки могут сломать систему , а пользователь даже и не будет знать что это именно из за этих линков фактически мусорных по этому удалите их обычно четыре штуки образуется в процессе установки можно смотреть внутрь корня / при установке ядер как я понял ядра как то смерживаются и сталкиваюся и по этому образуются мусорные линки , хотя если сначала удалить именно установленное ядро и фактически уже без ядер установить кернел то этих ссылок возможно не будет.

linux-headers-4.4.0-116_4.4.0-116.140_all.deb

linux-headers-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-4.4.0-116-generic_4.4.0-116.140_amd64.deb

linux-image-extra-4.4.0-116-generic_4.4.0-116.140_amd64.deb

---------------------------------------------------------------------

Установка именно готового пакета

sudo dpkg -i mesa_13.0.4-1_amd64.deb

Это свободная реалезация и любые xorg.conf должны быть обязательно удалены как сказано выше я посмотрю потом как можно разогнать по другому. Так же должна быть удалена папка со всем содержимым если она есть /etc/X11/xorg.d

Replace | заменяет mesa , libegl1-mesa-dev , mesa-common-dev , libgles2-mesa-dev , libosmesa6-dev , libgl1-mesa-dri:amd64 , libgl1-mesa-dri:i386 , libgbm-dev:amd64 , libegl1-mesa-dev

Состоит в таких группах video , games , users , kvm , voice , colord , pulse , pulse-access , bluetooth , rdma , irc , playonlinux , wine

Uninstall mesa_13.0.4 synaptic find griggorii@gmail.com update install reinstall mesa standart repository mesa

Помочь в разработке графического стека можно по ссылке https://money.yandex.ru/to/410014999913799 

