# developer.amperecomputing.com

## Ampere’s Commitment to Enabling Open Source Developers

Ampere is committed to enabling Aarch64 as a server platform and removing the barrier-to-entry for server based Aarch64 development within open-source project ecosystems. By contributing our Aarch64 platforms to projects, organizations, technology stakeholders, and by engaging in strategic partnerships with the projects themselves, we can help enable and ensure packages and binary artifacts are compiled natively on Aarch64 server platforms for Aarch64 architectures without using cross compilation.   Ampere is committed to ensuring Open source developers have a choice and can request access to Ampere Aarch64 platforms through one of our open source hosting partner providers:

### Equinix Metal 

* A commercial baremetal cloud infrastructure provider supporting Ampere compute platforms for several years.
* Provides Ampere resources to OpenSource projects through WorksOnArm, CNCF CI and other OSS initiatives.
* Equinix Metal information can be found here: [https://metal.equinix.com/](https://metal.equinix.com/)

### Oregon State University Open Source Labs

* One of the original open source hosting providers with 27 years providing open source infrastructure hosting across multiple compute Architectures
* 160 Projects hosted (… Apache, Linux Foundation, Drupal)
* Request access to Ampere reousrces at OSUOSL here: [https://osuosl.org/services/aarch64/request_hosting](https://osuosl.org/services/aarch64/request_hosting)

### FoSSHost.org/Aarch64.com

* A relatively new and quickly growing pure play open source hosting provider.
* Provides datacenter infrastructure and services to support open source projects
* Hosted projects include: Armbian, Debian, Rocky Linux, XFCE, Free Software Foundation Europe, KDE, GNU Health, QEMU
* Request Access to Ampere resources at FoSSHost.org here: [https://fosshost.org/apply](https://fosshost.org/apply)

## Compilers and Tools
Ampere has new GCC 10.2 compilers for CentOS 8.2.  The C,C++, and Fortran compilers are targeted for building high performance applications on Ampere aarch64 systems.  To install first download [gcc10.2](https://github.com/AmpereComputing/ampere-gcc/) on your Ampere Altra system then execute the following commands:

```
tar xf ampere-gcc-10.2.1-CentOS-8.2.2004-11378.tgz
source ./setup_env.sh
```
Now you’re ready to use Ampere’s GCC 10.2 compilers.

If you need support, please submit your issue at
https://github.com/AmpereComputing/ampere-gcc/issues
(Support is only provided for GCC10.2 on CentOS 8.2).

source code for the compiler is at https://github.com/AmpereComputing/ampere-gcc.

Previous versions of the Ampere compilers are available for download below.

### For Linux aarch64 hosted compilers and tools

#### 9.3.0:
* [Download: ampere-9.3.0-20200410-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-nativetools.tar.xz)
* [Download: ampere-9.3.0-20200410-dynamic-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-dynamic-nativetools.tar.xz)
* [Download: ampere-9.3.0-20200410-dynamic-nosysroot-nativetools.tar.xz](https://ampere-cdn.s3-us-west-2.amazonaws.com/tools/compilers/native/9.3.0/ampere-9.3.0-20200410-nosysroot-nativetools.tar.xz)

#### 8.4.0:

* [Download: ampere-8.4.0-20200327-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-nativetools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-dynamic-nativetools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nosysroot-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.4.0/ampere-8.4.0-20200327-dynamic-nosysroot-nativetools.tar.xz)

#### 8.3.0:

* [Download: ampere-8.3.0-20191025-dynamic-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20191025-dynamic-nativetools.tar.xz)
* [Download: ampere-8.3.0-20191025-dynamic-nosysroot-nativetools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20191025-dynamic-nosysroot-nativetools.tar.xz)
* [Download: ampere-8.3.0-nativetools-20190830.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.3.0/ampere-8.3.0-20190830-nativetools.tar.xz)

#### 8.2.0:

* [Download: ampere-8.2.0-nativetools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/native/8.2.0/ampere-8.2.0-nativetools-20180930.tar.xz)

#### 7.3.0:

* [Download: ampere-7.3.0-nativetools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/native/7.3.0/ampere-7.3.0-nativetools-20180930.tar.xz)

### For Linux x86-64 hosted cross-compilers and tools targeting aarch64:

#### 9.3.0:

* [Download: ampere-9.3.0-20200331-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-crosstools.tar.xz)
* [Download: ampere-9.3.0-20200331-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-dynamic-crosstools.tar.xz)
* [Download: ampere-9.3.0-20200331-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/9.3.0/ampere-9.3.0-20200331-dynamic-nosysroot-crosstools.tar.xz)

#### 8.4.0:

* [Download: ampere-8.4.0-20200327-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-crosstools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-dynamic-crosstools.tar.xz)
* [Download: ampere-8.4.0-20200327-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.4.0/ampere-8.4.0-20200327-dynamic-nosysroot-crosstools.tar.xz)

#### 8.3.0:

* [Download: ampere-8.3.0-20191025-dynamic-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20191025-dynamic-crosstools.tar.xz)
* [Download: ampere-8.3.0-20191025-dynamic-nosysroot-crosstools.tar.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20191025-dynamic-nosysroot-crosstools.tar.xz)
* [Download: ampere-8.3.0-crosstools-20190830.xz](http://cdn.amperecomputing.com/tools/compilers/cross/8.3.0/ampere-8.3.0-20190830-crosstools.tar.xz)

#### 8.2.0:

* [Download: ampere-8.2.0-crosstools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/cross/8.2.0/ampere-8.2.0-crosstools-20180930.tar.xz)

#### 7.3.0:

* [Download: ampere-7.3.0-crosstools-20180930.xz](https://cdn.amperecomputing.com/tools/compilers/cross/7.3.0/ampere-7.3.0-crosstools-20180930.tar.xz)

## Helpful Guides

* [How To: Patch Tools/Perf to Enable Ampere Vendor Counters](https://cdn.amperecomputing.com/documentation/kernel/tools/perf/Ampere-eMAG-HowTo-Patch-Perf-Counters.pdf)

## Open Source Community Mentions

* [https://www.debian.org/News/2020/20200616](https://www.debian.org/News/2020/20200616)
* [https://lists.freebsd.org/pipermail/freebsd-announce/2021-April/002030.html](https://lists.freebsd.org/pipermail/freebsd-announce/2021-April/002030.html)
* [https://www.openmandriva.org/en/news/article/openmandriva-build-infrastructure-switches-to-arm-servers](https://www.openmandriva.org/en/news/article/openmandriva-build-infrastructure-switches-to-arm-servers)
* [https://kali.org/blog/ampere/](https://kali.org/blog/ampere/)
