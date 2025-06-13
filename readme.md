# `msys_setup`

This is a set of scripts that set up an MSYS/MinGW environment on Windows and allow compiling `libvirt` and related libraries and tools.

## Is this what you're looking for?

- If you want a prebuilt Windows installer for libvirt, rather than compiling from source yourself, take a look at http://libvirt.org/windows.html.

- That installer is for quite an old version by now, and it includes 32-bit binaries only. More recent libvirt binaries for 32-bit and 64-bit are part of the `virt-viewer` installer for Windows that can be downloaded from http://spice-space.org/download.html.

## General MSYS/MinGW environment setup

- Download `wget.exe` from http://users.ugent.be/~bpuype/wget/ and put it in the same directory as `msys_setup.bat`.

- Run `msys_setup.bat` to download and set up an MSYS/MinGW environment.

  You'll see automated Windows Installer popups for 7-Zip and Python. The script is not actually installing something to your system, it just unpacks both into subdirectories for later use.

  When you have UAC enabled (Windows Vista and Windows 7), then Windows will ask you for confirmation, you need to allow 7zip and Python to get unpacked

### Compiling `libvirt`

See `readme_libvirt.txt`.

### Setting up `virt-manager`

See `readme_virt-manager.txt`.
