# GPIB
GPIB sample code library
This section provides step-by-step guides for installing and using two widely used USB-GPIB adapters on Ubuntu and Windows 11. Each guide covers adapter setup, communication testing with GPIB utilities, and practical Python programming examples.

[Agilent USB-GPIB 82357B on Ubuntu24.04, 26.04](https://n7sd.com/ada1-2/agilent-usb-gpib-82357b-on-ubuntu24-04-26-04/)

This guide describes how to install and use an **Agilent USB-GPIB Interface 82357B** adapter on Ubuntu 24.04 and Ubuntu 26.04 using **Linux-GPIB 4.3.7**.

The setup procedure for this adapter is almost the same as that for the NI GPIB-USB-HS  when using Linux-GPIB. However, the procedure is slightly shorter because this adapter does not require an additional patch or configuration of `gpib.conf`.


[Agilent USB-GPIB 82357B on Windows11](https://n7sd.com/ada1-2/agilent-usb-gpib-82357b-on-windows11/)

This guide describes how to install and use an **Agilent USB-GPIB Interface 82357B** adapter on Windows 11 using **Keysight IO Libraries Suite**.

The Agilent USB-GPIB 82357B can be used simply by installing the Keysight IO Libraries Suite software package.

Several standard graphical utility applications are installed together with the library, allowing you to easily check the operation of the GPIB adapter and connected GPIB devices.

Some simple examples of how to use these utilities are provided for reference.


[NI GPIB-USB-HS on Ubuntu 24.04, 26.04](https://n7sd.com/ada1-2/ni-gpib-usb-hs-on-ubuntu-24-04-26-04/)

This guide describes how to install and use an **National Instruments GPIB-USB-HS** on Ubuntu 24.04 and Ubuntu 26.04 using **Linux-GPIB 4.3.7**.

The particular adapter used in this project requires a modification to the ni_usb_gpib.c file because its identification sequence during startup differs from what the original Linux-GPIB driver expects. I prepared the required modifications as a patch file so that they can be applied easily. The patch code is provided at the end of this page and on GitHub for downloading.


[NI GPIB-USB-HS on Windows 11](https://n7sd.com/ada1-2/ni-gpib-usb-hs-on-windows-11/)

This guide describes how to install and use an **National Instruments GPIB-USB-HS** on Windows 11 using **NI-488.2**.

The NI GPIB-USB-HS can be used simply by installing NI’s standard NI-488.2 software package.

Several standard graphical utility applications are installed together with NI-488.2, allowing you to easily check the operation of the GPIB adapter and connected GPIB devices.

Some simple examples of how to use these utilities are provided below for reference.

<p>
<img width="300" alt="AGI-82357B-IMG_8681" src="https://github.com/user-attachments/assets/a0e6b206-1fc1-48e3-9860-303c1617fc21" />
<img width="400" alt="NI-GPIB-IMG_8676a" src="https://github.com/user-attachments/assets/3447d99c-4461-4140-907f-d7c5debddb11" />
</p>
<p>
<img width="300" alt="34401A-Front" src="https://github.com/user-attachments/assets/a35acad0-cf0d-4928-8b10-43fa6c6bf7f5" />
<img width="300" alt="1x34401A NI AGI UB" src="https://github.com/user-attachments/assets/c4b1615d-5aed-4483-9a8c-f19c5072ad3f" />
</p>
<p>
<img width="300" alt="3x34401A Datalogger Window" src="https://github.com/user-attachments/assets/9c8b4225-8753-4c1b-9f60-8acc3036130d" />
<img width="400" alt="3x34401A-Front" src="https://github.com/user-attachments/assets/6cde26bc-1253-4011-99cd-41f7c7ce1ead" />
</p>
