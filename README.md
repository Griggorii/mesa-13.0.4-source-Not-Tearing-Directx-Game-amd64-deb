# mesa-13.0.4-source-Not-Tearing-Directx-Game-amd64-deb
deb , mesa , source , 13.0.4 , Not , Tearing , Directx9 , Directx11 , window , amd64 , debian , ubuntu

llvm-9.0.1_1-1_amd64.deb https://drive.google.com/open?id=1COizcVRsss84l_tLQdxzu2LMFM1J8i_v replace llvm standart

sudo dpkg -i llvm-9.0.1_1-1_amd64.deb

Run in folder terminal mesa-13.0.4

./configure --prefix=/usr --exec-prefix=/usr/lib/x86_64-linux-gnu/ --enable-glx-tls --enable-driglx-direct --enable-xa --enable-texture-float --enable-osmesa --enable-gles1 --enable-gles2 --enable-opencl-icd --with-dri-driverdir=/usr/lib/x86_64-linux-gnu/dri --with-gallium-drivers=r300,r600,radeonsi,svga,swrast --enable-autotools --with-gallium-drivers=r600 --disable-gallium-llvm --enable-sysfs --with-egl-platforms="drm,x11"

make -j16
