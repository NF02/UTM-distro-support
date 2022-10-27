# UTM distro support
This is a list of Linux and Unix distributions or other os that start on UTM, the virtualization program for Mac with Apple Silicon M and Iphone.
The idea of the project is to map all the working distros within the environment creating a stable and reliable environment.

|       OS             |      Arch     |   version  |    status   |   UTM       |   product     |   Host OS    |
|----------------------|---------------|------------|-------------| ----------- | ------------- | ------------ |
|     **<a href="https://github.com/NF02/UTM-distro-support/blob/main/report/Debian11.md">Debian Linux</a>**       |     arm64     |     11     |      ☑      |  4.0.9      | mbpro m1 8gb  |  13 Ventura  |
|     **<a href="href="https://github.com/NF02/UTM-distro-support/blob/main/report/kali2022-3.md">Kali Linux</a>**   |     arm64     |  2022.3    |      ⚠      |  4.0.9      | mbpro m1 8gb  |  13 Ventura  |
|     **Gentoo Linux** |     arm64     |   rolling  |      ⚠      |  3.0.6      | mbpro m1 8gb  |  12 Monterey |
|     **Fedora Linux** |     arm64     |     36     |      ☑      |  4.0.9      | mbpro m1 8gb  |  13 Ventura  |
|     **<a href="https://github.com/NF02/UTM-distro-support/blob/main/report/Ubuntu-2004.md">Ubuntu Linux</a>** |     arm64     |     20.04  |      ⚠      |  3.0.6      | mbpro m1 8gb  |  12 Monterey |
|     **<a href="https://github.com/NF02/UTM-distro-support/blob/main/report/Ubuntu-2204.md">Ubuntu Linux</a>** |     arm64     |     22.04  |      ⚠      |  3.0.6      | mbpro m1 8gb  |  12 Monterey |

- ☑ works out of the box;
- ⚠ it works but is not very stable;
- ~ in testing right now;
- 🚫 It does not work.

## What are the main problems of UTM?
- Guest additions sometimes do not go or do not perfectly recognize the resolution used by the host system at that moment.
- Sometimes distros don't boot from live cd or iso image.

# How can you help the project?
for those wishing to contribute there are two ways:
- the first is to do some tests if you have the aforementioned hardware;
- the second is a donation on ko-fi.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A3CDMP9)
