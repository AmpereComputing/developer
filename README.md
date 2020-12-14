Whether you’re looking to enhance the functionality of your app or optimize its performance, Ampere offers you the software tools and resources to bring out the best in your development.

# Getting Started
                  
* [Ampere eMAG Developer Platform – Order Now](https://forms.na3.netsuite.com/app/site/crm/externalleadpage.nl?compid=4930892&amp;formid=1&amp;h=AACffht_TmseBAYK-ad3GeFCHCWaEv5F4e8)
* [Try Us Out @ Works on Arm](https://www.worksonarm.com)
* [Video Guide: Getting Started with Ampere eMAG Hardware](https://www.youtube.com/watch?v=NMCveQIyAEM)

# Software Development Environment
                  
## Developer Documentation:

* [eMAG 8180 Product Brief](https://cdn.amperecomputing.com/documentation/hardware/eMAG/eMAG8180_PB_v0.5_20180914.pdf)
* [eMAG Perf Events Reference Sheet](https://cdn.amperecomputing.com/documentation/kernel/tools/perf/Ampere-eMAG-CoreImpDefined-PMU-Events.pdf)
* [Ampere CentOS Kernel Wiki]https://github.com/AmpereComputing/ampere-centos-kernel/wiki/Ampere-CentOS-Kernel-wiki)

## Compilers and Tools
The new Ampere Gcc 8.4 and 9.3 compilers have the latest bug fixes and support for Ampere’s Altra™ processors. These compilers will default to targeting the Ampere Altra™ processor (mcpu=neoverse-n1), supporting the new instructions and tuning for the microarchitecture.
The ‘sysroot’ compilers provide a set of optimized libraries in the `.tar.gz` archive: these can be linked statically with your program or are available for dynamically linked executable with a custom library search path. The ‘nosysroot’ compiler is intended to build binaries that use the libraries on the system you are running on in the system search path—it acts as a drop-in replacement for your system compiler.
If you’re looking for the best performance, try the ‘-Ofast’ (highest optimization setting) and ‘-flto’ (link-time optimizations) options.

## For Linux aarch64 hosted compilers and tools

### 9.3.0:
* [Download: ampere-9.3.0-20200410-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-nativetools.tar.xz)
* [Download: ampere-9.3.0-20200410-dynamic-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-dynamic-nativetools.tar.xz)
* [Download: ampere-9.3.0-20200410-dynamic-nosysroot-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-nosysroot-nativetools.tar.xz)

### 8.4.0:

* [Download: ampere-8.4.0-20200327-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-nativetools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-dynamic-nativetools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nosysroot-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-dynamic-nosysroot-nativetools.tar.xz)

### 8.3.0:

* [Download: ampere-8.3.0-20191025-dynamic-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20191025-dynamic-nativetools.tar.xz)
* [Download: ampere-8.3.0-20191025-dynamic-nosysroot-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20191025-dynamic-nosysroot-nativetools.tar.xz)
* [Download: ampere-8.3.0-nativetools-20190830.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20190830-nativetools.tar.xz)

### 8.2.0:

* [Download: ampere-8.2.0-nativetools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.2.0/ampere-8.2.0-nativetools-20180930.tar.xz)

### 7.3.0:

* [Download: ampere-7.3.0-nativetools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/native/7.3.0/ampere-7.3.0-nativetools-20180930.tar.xz)

## For Linux x86-64 hosted cross-compilers and tools targeting aarch64:

### 9.3.0:

* [Download: ampere-9.3.0-20200331-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-crosstools.tar.xz)
* [Download: ampere-9.3.0-20200331-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-dynamic-crosstools.tar.xz)
* [Download: ampere-9.3.0-20200331-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-dynamic-nosysroot-crosstools.tar.xz)

### 8.4.0:

* [Download: ampere-8.4.0-20200327-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-crosstools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-dynamic-crosstools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-dynamic-nosysroot-crosstools.tar.xz)

### 8.3.0:

* [Download: ampere-8.3.0-20191025-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20191025-dynamic-crosstools.tar.xz)
* [Download: ampere-8.3.0-20191025-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20191025-dynamic-nosysroot-crosstools.tar.xz)
* [Download: ampere-8.3.0-crosstools-20190830.xz](http://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20190830-crosstools.tar.xz)

### 8.2.0:

* [Download: ampere-8.2.0-crosstools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.2.0/ampere-8.2.0-crosstools-20180930.tar.xz)

### 7.3.0:

* [Download: ampere-7.3.0-crosstools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/cross/7.3.0/ampere-7.3.0-crosstools-20180930.tar.xz)

## Ampere eMAG(tm) support

| Operating System | Recommended Version |
| --- | --- |
| CentOS | >= 7.5 |
| Fedora | >= 27 |
| OracleLinux | >= 7.5 |
| RedHat Enterprise Linux (RHEL) | >= 7.5 | 
| Ubuntu | >= 18.04.01 |
