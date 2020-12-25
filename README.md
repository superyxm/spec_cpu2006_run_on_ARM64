# spec_cpu2006_run_on_ARM64
This is tutorial for running spec_cpu2006 on ARM64 devices.
I validated this tutorial on NVIDA Jetson Nano. Maybe I will validate on RasbpberryPi 4.

1. Firstly,you need to get cpu2006 source file. It is a iso file. The source file needs license so I cannot provide this here.
Then uncompress the ISO file.

2. Then you need to download the tools for arm64, here is the website:https://www.spec.org/cpu2006/src.alt/
Download linux-apm-arm64-118.tar, then uncompress the file.

3. Replace the tools file with the file download in step2.

4. Then，run sh ./install.sh

5. When you find some errors, donwgrade you gcc,g++,gfortran.
