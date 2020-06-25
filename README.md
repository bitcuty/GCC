# GCC
## Installation GCC Software

sudo apt-cyg install wget gcc-g++ make diffutils libmpfr-devel libgmp-devel libmpc-devel libpcre-devel libcrypt-devel
wget http://ftpmirror.gnu.org/gcc/gcc-4.9.2/gcc-4.9.2.tar.gz
tar xf gcc-4.9.2.tar.gz
mkdir build-gcc && cd build-gcc
../gcc-4.9.2/configure --program-suffix=-4.9.2 --enable-languages=c,c++ --disable-bootstrap --disable-shared
make -j4
make install
Finally build gsl:
git clone git://github.com/imatix/gsl
cd gsl/src
make
make install
cd
./generate.sh

## Installation GCC Package

sudo apt install -y	cpp  # GNU C preprocessor (cpp)
sudo apt install -y	cpp-7  # GNU C preprocessor
sudo apt install -y	cpp-7-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-7-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-aarch64-linux-gnu  # GNU C preprocessor (cpp) for the arm64 architecture
sudo apt install -y	cpp-arm-linux-gnueabihf  # GNU C preprocessor (cpp) for the armhf architecture
sudo apt install -y	cpp-powerpc-linux-gnu  # GNU C preprocessor (cpp) for the powerpc architecture
sudo apt install -y	cpp-powerpc64le-linux-gnu  # GNU C preprocessor (cpp) for the ppc64el architecture
sudo apt install -y	dpkg-dev  # Debian package development tools
sudo apt install -y	gcc  # GNU C compiler
sudo apt install -y	gcc-7  # GNU C compiler
sudo apt install -y	gcc-7-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-cross-base  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-7-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-7-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-aarch64-linux-gnu  # GNU C compiler for the arm64 architecture
sudo apt install -y	gcc-arm-linux-gnueabihf  # GNU C compiler for the armhf architecture
sudo apt install -y	gcc-multilib  # GNU C compiler (multilib files)
sudo apt install -y	gcc-powerpc-linux-gnu  # GNU C compiler for the powerpc architecture
sudo apt install -y	gcc-powerpc64le-linux-gnu  # GNU C compiler for the ppc64el architecture
sudo apt install -y	gfortran  # GNU Fortran 95 compiler
sudo apt install -y	gfortran-7  # GNU Fortran compiler
sudo apt install -y	gfortran-7-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-multilib  # GNU Fortran 95 compiler (multilib files)
sudo apt install -y	golang-go  # Go programming language compiler, linker, compiled stdlib
sudo apt install -y	lib32atomic1  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-dbg  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32gcc-7-dev  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc1  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-dbg  # GCC support library (debug symbols)
sudo apt install -y	lib32gomp1  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-dbg  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32quadmath0  # GCC Quad-Precision Math Library (32bit)
sudo apt install -y	lib32quadmath0-dbg  # GCC Quad-Precision Math Library (32 bit debug symbols)
sudo apt install -y	libatomic1  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-arm64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-armhf-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-dbg  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-powerpc-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-ppc64el-cross  # support library providing __atomic built-in functions
sudo apt install -y	libcc1-0  # GCC cc1 plugin for GDB
sudo apt install -y	libgcc-7-dev  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc1  # GCC support library
sudo apt install -y	libgcc1-dbg  # GCC support library (debug symbols)
sudo apt install -y	libgccjit-7-dev  # GCC just-in-time compilation (development files)
sudo apt install -y	libgccjit-7-doc  # GCC just-in-time compilation (documentation)
sudo apt install -y	libgccjit0  # GCC just-in-time compilation (shared library)
sudo apt install -y	libgccjit0-dbg  # GCC just-in-time compilation (debug information)
sudo apt install -y	libgomp1  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-arm64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-armhf-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-dbg  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-powerpc-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-ppc64el-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libquadmath0  # GCC Quad-Precision Math Library
sudo apt install -y	libquadmath0-dbg  # GCC Quad-Precision Math Library (debug symbols)
sudo apt install -y	libx32atomic1  # support library providing __atomic built-in functions (x32)
sudo apt install -y	libx32atomic1-dbg  # support library providing __atomic built-in functions (x32 debug symbols)
sudo apt install -y	libx32gcc-7-dev  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc1  # GCC support library (x32)
sudo apt install -y	libx32gcc1-dbg  # GCC support library (debug symbols)
sudo apt install -y	libx32gomp1  # GCC OpenMP (GOMP) support library (x32)
sudo apt install -y	libx32gomp1-dbg  # GCC OpenMP (GOMP) support library (x32 debug symbols)
sudo apt install -y	libx32quadmath0  # GCC Quad-Precision Math Library (x32)
sudo apt install -y	libx32quadmath0-dbg  # GCC Quad-Precision Math Library (x32 debug symbols)
sudo apt install -y	uno-libs3  # LibreOffice UNO runtime environment -- public shared libraries
sudo apt install -y	lib64atomic1  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64atomic1-dbg  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64gcc-7-dev  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc1  # GCC support library (64bit)
sudo apt install -y	lib64gcc1-dbg  # GCC support library (debug symbols)
sudo apt install -y	lib64gomp1  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	lib64gomp1-dbg  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64quadmath0  # GCC Quad-Precision Math Library  (64bit)
sudo apt install -y	lib64quadmath0-dbg  # GCC Quad-Precision Math Library  (64bit debug symbols)
sudo apt install -y	gcc-7-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-8-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-cross-base  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-doc  # Documentation for the GNU C compilers (gcc, gobjc, g++)
sudo apt install -y	gccgo-7-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-8-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-doc  # Documentation for the GNU Go compiler
sudo apt install -y	lib32gcc-8-dev  # GCC support library (32 bit development files)
sudo apt install -y	libclang1-6.0  # C interface to the clang library
sudo apt install -y	libgccjit-8-dev  # GCC just-in-time compilation (development files)
sudo apt install -y	libx32gcc-8-dev  # GCC support library (x32 development files)
sudo apt install -y	lib64gcc-8-dev  # GCC support library (64bit development files)
sudo apt install -y	autoconf2.64  # automatic configure script builder (obsolete version)
sudo apt install -y	autofdo  # AutoFDO Profile Toolchain
sudo apt install -y	binutils-mingw-w64  # Cross-binutils for Win32 and Win64 using MinGW-w64
sudo apt install -y	binutils-mingw-w64-i686  # Cross-binutils for Win32 (x86) using MinGW-w64
sudo apt install -y	binutils-mingw-w64-x86-64  # Cross-binutils for Win64 (x64) using MinGW-w64
sudo apt install -y	castxml  # C-family abstract syntax tree XML output tool
sudo apt install -y	clang-3.9  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-3.9-doc  # C, C++ and Objective-C compiler (LLVM based)  # Documentation
sudo apt install -y	clang-3.9-examples  # Clang examples
sudo apt install -y	clang-5.0-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	cpp-4.8  # GNU C preprocessor
sudo apt install -y	cpp-5  # GNU C preprocessor
sudo apt install -y	cpp-5-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-alpha-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-5-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-5-m68k-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-mips-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-mips64-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-5-mips64el-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-5-mipsel-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-powerpc-linux-gnuspe  # GNU C preprocessor
sudo apt install -y	cpp-5-powerpc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-s390x-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-sh4-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-sparc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-alpha-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-6-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-6-hppa-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-m68k-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-mips-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-mips64-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-6-mips64el-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-6-mipsel-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-powerpc-linux-gnuspe  # GNU C preprocessor
sudo apt install -y	cpp-6-powerpc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-s390x-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-sh4-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-sparc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-alpha-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-7-hppa-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-m68k-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-mips-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-mips64-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-7-mips64el-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-7-mipsel-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-powerpc-linux-gnuspe  # GNU C preprocessor
sudo apt install -y	cpp-7-powerpc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-s390x-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-sh4-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-sparc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-alpha-linux-gnu  # GNU C preprocessor (cpp) for the alpha architecture
sudo apt install -y	cpp-arm-linux-gnueabi  # GNU C preprocessor (cpp) for the armel architecture
sudo apt install -y	cpp-hppa-linux-gnu  # GNU C preprocessor (cpp) for the hppa architecture
sudo apt install -y	cpp-m68k-linux-gnu  # GNU C preprocessor (cpp) for the m68k architecture
sudo apt install -y	cpp-mips-linux-gnu  # GNU C preprocessor (cpp) for the mips architecture
sudo apt install -y	cpp-mips64-linux-gnuabi64  # GNU C preprocessor (cpp) for the mips64 architecture
sudo apt install -y	cpp-mips64el-linux-gnuabi64  # GNU C preprocessor (cpp) for the mips64el architecture
sudo apt install -y	cpp-mipsel-linux-gnu  # GNU C preprocessor (cpp) for the mipsel architecture
sudo apt install -y	cpp-powerpc-linux-gnuspe  # GNU C preprocessor (cpp) for the powerpcspe architecture
sudo apt install -y	cpp-powerpc64-linux-gnu  # GNU C preprocessor (cpp) for the ppc64 architecture
sudo apt install -y	cpp-s390x-linux-gnu  # GNU C preprocessor (cpp) for the s390x architecture
sudo apt install -y	cpp-sh4-linux-gnu  # GNU C preprocessor (cpp) for the sh4 architecture
sudo apt install -y	cpp-sparc64-linux-gnu  # GNU C preprocessor (cpp) for the sparc64 architecture
sudo apt install -y	cpphs  # Simplified cpp-a-like preprocessor for Haskell
sudo apt install -y	cross-gcc-dev  # Tools for building cross-compilers and cross-compiler packages
sudo apt install -y	cstream  # general-purpose stream-handling tool similar to dd
sudo apt install -y	cxref  # Generates LaTeX and HTML documentation for C programs
sudo apt install -y	eclipse-cdt-pkg-config  # pkg-config support for Eclipse C/C++ development tools
sudo apt install -y	g++-mingw-w64  # GNU C++ compiler for MinGW-w64
sudo apt install -y	g++-mingw-w64-i686  # GNU C++ compiler for MinGW-w64 targeting Win32
sudo apt install -y	g++-mingw-w64-x86-64  # GNU C++ compiler for MinGW-w64 targeting Win64
sudo apt install -y	gcc-4.8  # GNU C compiler
sudo apt install -y	gcc-4.8-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.8-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-4.8-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.8-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-4.8-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-5  # GNU C compiler
sudo apt install -y	gcc-5-aarch64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-alpha-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-alpha-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-arm-linux-gnueabi  # GNU C compiler
sudo apt install -y	gcc-5-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-arm-linux-gnueabihf  # GNU C compiler
sudo apt install -y	gcc-5-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-cross-base  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-5-cross-base-ports  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-5-hppa64-linux-gnu  # GNU C compiler (cross compiler for hppa64)
sudo apt install -y	gcc-5-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-5-m68k-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-m68k-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-mips-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-mips-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-mips64-linux-gnuabi64  # GNU C compiler
sudo apt install -y	gcc-5-mips64-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-mips64el-linux-gnuabi64  # GNU C compiler
sudo apt install -y	gcc-5-mips64el-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-mipsel-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-mipsel-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-arm-linux-gnueabi  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-mips-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-mips64-linux-gnuabi64  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-mips64el-linux-gnuabi64  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-mipsel-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-powerpc64-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-s390x-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-sparc64-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-aarch64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-alpha-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-arm-linux-gnueabi  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-arm-linux-gnueabihf  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-m68k-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-mips-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-mips64-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-mips64el-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-mipsel-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-powerpc-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-powerpc-linux-gnuspe  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-powerpc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-powerpc64le-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-s390x-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-sh4-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-sparc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-powerpc-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-powerpc-linux-gnuspe  # GNU C compiler
sudo apt install -y	gcc-5-powerpc-linux-gnuspe-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-powerpc64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-powerpc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-powerpc64le-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-s390x-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-s390x-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-sh4-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-sh4-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-5-sparc64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-sparc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-test-results  # Test results for the GCC test suite
sudo apt install -y	gcc-6-aarch64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-alpha-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-alpha-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-arm-linux-gnueabi  # GNU C compiler
sudo apt install -y	gcc-6-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-arm-linux-gnueabihf  # GNU C compiler
sudo apt install -y	gcc-6-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-cross-base  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-6-cross-base-ports  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-6-hppa-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-hppa-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-hppa64-linux-gnu  # GNU C compiler (cross compiler for hppa64)
sudo apt install -y	gcc-6-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-6-m68k-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-m68k-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-mips-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-mips-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-mips64-linux-gnuabi64  # GNU C compiler
sudo apt install -y	gcc-6-mips64-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-mips64el-linux-gnuabi64  # GNU C compiler
sudo apt install -y	gcc-6-mips64el-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-mipsel-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-mipsel-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-arm-linux-gnueabi  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-mips-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-mips64-linux-gnuabi64  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-mips64el-linux-gnuabi64  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-mipsel-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-powerpc64-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-s390x-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-sparc64-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-plugin-dev-aarch64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-alpha-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-arm-linux-gnueabi  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-arm-linux-gnueabihf  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-hppa-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-m68k-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-mips-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-mips64-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-mips64el-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-mipsel-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-powerpc-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-powerpc-linux-gnuspe  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-powerpc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-powerpc64le-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-s390x-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-sh4-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-sparc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-powerpc-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-powerpc-linux-gnuspe  # GNU C compiler
sudo apt install -y	gcc-6-powerpc-linux-gnuspe-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-powerpc64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-powerpc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-powerpc64le-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-s390x-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-s390x-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-sh4-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-sh4-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-6-sparc64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-sparc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-test-results  # Test results for the GCC test suite
sudo apt install -y	gcc-7-alpha-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-hppa-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-hppa64-linux-gnu  # GNU C compiler (cross compiler for hppa64)
sudo apt install -y	gcc-7-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-7-m68k-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-mips-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-mips64-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-mips64el-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-mipsel-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-plugin-dev-aarch64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-alpha-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-arm-linux-gnueabi  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-arm-linux-gnueabihf  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-hppa-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-m68k-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-mips-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-mips64-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-mips64el-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-mipsel-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-powerpc-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-powerpc-linux-gnuspe  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-powerpc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-powerpc64le-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-s390x-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-sh4-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-sparc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-powerpc-linux-gnuspe-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-powerpc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-s390x-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-sh4-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-7-sparc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-test-results  # Test results for the GCC test suite
sudo apt install -y	gcc-alpha-linux-gnu  # GNU C compiler for the alpha architecture
sudo apt install -y	gcc-arm-linux-gnueabi  # GNU C compiler for the armel architecture
sudo apt install -y	gcc-arm-none-eabi  # GCC cross compiler for ARM Cortex-A/R/M processors
sudo apt install -y	gcc-arm-none-eabi-source  # GCC cross compiler for ARM Cortex-A/R/M processors (source)
sudo apt install -y	gcc-avr  # GNU C compiler (cross compiler for avr)
sudo apt install -y	gcc-h8300-hms  # GNU C compiler (cross compiler for h8300-hitachi-coff)
sudo apt install -y	gcc-hppa-linux-gnu  # GNU C compiler for the hppa architecture
sudo apt install -y	gcc-hppa64-linux-gnu  # GNU C compiler (cross compiler for hppa64-linux-gnu)
sudo apt install -y	gcc-m68hc1x  # GNU C compiler for the Motorola 68HC11/12 processors
sudo apt install -y	gcc-m68k-linux-gnu  # GNU C compiler for the m68k architecture
sudo apt install -y	gcc-mingw-w64  # GNU C compiler for MinGW-w64
sudo apt install -y	gcc-mingw-w64-base  # GNU Compiler Collection for MinGW-w64 (base package)
sudo apt install -y	gcc-mingw-w64-i686  # GNU C compiler for MinGW-w64 targeting Win32
sudo apt install -y	gcc-mingw-w64-x86-64  # GNU C compiler for MinGW-w64 targeting Win64
sudo apt install -y	gcc-mips-linux-gnu  # GNU C compiler for the mips architecture
sudo apt install -y	gcc-mips64-linux-gnuabi64  # GNU C compiler for the mips64 architecture
sudo apt install -y	gcc-mips64el-linux-gnuabi64  # GNU C compiler for the mips64el architecture
sudo apt install -y	gcc-mipsel-linux-gnu  # GNU C compiler for the mipsel architecture
sudo apt install -y	gcc-msp430  # GNU C compiler (cross compiler for MSP430)
sudo apt install -y	gcc-multilib-arm-linux-gnueabi  # GNU C compiler for the armel architecture
sudo apt install -y	gcc-multilib-arm-linux-gnueabihf  # GNU C compiler for the armhf architecture
sudo apt install -y	gcc-multilib-mips-linux-gnu  # GNU C compiler for the mips architecture
sudo apt install -y	gcc-multilib-mips64-linux-gnuabi64  # GNU C compiler for the mips64 architecture
sudo apt install -y	gcc-multilib-mips64el-linux-gnuabi64  # GNU C compiler for the mips64el architecture
sudo apt install -y	gcc-multilib-mipsel-linux-gnu  # GNU C compiler for the mipsel architecture
sudo apt install -y	gcc-multilib-powerpc-linux-gnu  # GNU C compiler for the powerpc architecture
sudo apt install -y	gcc-multilib-powerpc64-linux-gnu  # GNU C compiler for the ppc64 architecture
sudo apt install -y	gcc-multilib-s390x-linux-gnu  # GNU C compiler for the s390x architecture
sudo apt install -y	gcc-multilib-sparc64-linux-gnu  # GNU C compiler for the sparc64 architecture
sudo apt install -y	gcc-powerpc-linux-gnuspe  # GNU C compiler for the powerpcspe architecture
sudo apt install -y	gcc-powerpc64-linux-gnu  # GNU C compiler for the ppc64 architecture
sudo apt install -y	gcc-python-plugin-doc  # plugin for GCC to invoke Python scripts from inside the compiler
sudo apt install -y	gcc-s390x-linux-gnu  # GNU C compiler for the s390x architecture
sudo apt install -y	gcc-sh4-linux-gnu  # GNU C compiler for the sh4 architecture
sudo apt install -y	gcc-snapshot  # SNAPSHOT of the GNU Compiler Collection
sudo apt install -y	gcc-sparc64-linux-gnu  # GNU C compiler for the sparc64 architecture
sudo apt install -y	gccgo  # Go compiler, based on the GCC backend
sudo apt install -y	gccgo-4.8  # GNU Go compiler
sudo apt install -y	gccgo-4.8-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5  # GNU Go compiler
sudo apt install -y	gccgo-5-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-alpha-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-5-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-5-mips-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-mips64-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-5-mips64el-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-5-mipsel-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-mips-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-mips64-linux-gnuabi64  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-mips64el-linux-gnuabi64  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-mipsel-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-powerpc64-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-s390x-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-sparc64-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-powerpc-linux-gnuspe  # GNU Go compiler
sudo apt install -y	gccgo-5-powerpc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-s390x-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-sparc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6  # GNU Go compiler
sudo apt install -y	gccgo-6-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-alpha-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-6-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-6-m68k-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-mips-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-mips64-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-6-mips64el-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-6-mipsel-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-mips-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-mips64-linux-gnuabi64  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-mips64el-linux-gnuabi64  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-mipsel-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-powerpc64-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-s390x-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-sparc64-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-powerpc-linux-gnuspe  # GNU Go compiler
sudo apt install -y	gccgo-6-powerpc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-s390x-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-sparc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7  # GNU Go compiler
sudo apt install -y	gccgo-7-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-alpha-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-7-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-7-mips-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-mips64-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-7-mips64el-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-7-mipsel-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-7-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-powerpc-linux-gnuspe  # GNU Go compiler
sudo apt install -y	gccgo-7-powerpc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-s390x-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-sparc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-aarch64-linux-gnu  # Go compiler (based on GCC) for the arm64 architecture
sudo apt install -y	gccgo-alpha-linux-gnu  # Go compiler (based on GCC) for the alpha architecture
sudo apt install -y	gccgo-arm-linux-gnueabi  # Go compiler (based on GCC) for the armel architecture
sudo apt install -y	gccgo-arm-linux-gnueabihf  # Go compiler (based on GCC) for the armhf architecture
sudo apt install -y	gccgo-go  # Go programming language -- gccgo
sudo apt install -y	gccgo-mips-linux-gnu  # Go compiler (based on GCC) for the mips architecture
sudo apt install -y	gccgo-mips64-linux-gnuabi64  # Go compiler (based on GCC) for the mips64 architecture
sudo apt install -y	gccgo-mips64el-linux-gnuabi64  # Go compiler (based on GCC) for the mips64el architecture
sudo apt install -y	gccgo-mipsel-linux-gnu  # Go compiler (based on GCC) for the mipsel architecture
sudo apt install -y	gccgo-multilib  # Go compiler, based on the GCC backend (multilib files)
sudo apt install -y	gccgo-multilib-mips-linux-gnu  # Go compiler (based on GCC) for the mips architecture
sudo apt install -y	gccgo-multilib-mips64-linux-gnuabi64  # Go compiler (based on GCC) for the mips64 architecture
sudo apt install -y	gccgo-multilib-mips64el-linux-gnuabi64  # Go compiler (based on GCC) for the mips64el architecture
sudo apt install -y	gccgo-multilib-mipsel-linux-gnu  # Go compiler (based on GCC) for the mipsel architecture
sudo apt install -y	gccgo-multilib-powerpc-linux-gnu  # Go compiler (based on GCC) for the powerpc architecture
sudo apt install -y	gccgo-multilib-powerpc64-linux-gnu  # Go compiler (based on GCC) for the ppc64 architecture
sudo apt install -y	gccgo-multilib-s390x-linux-gnu  # Go compiler (based on GCC) for the s390x architecture
sudo apt install -y	gccgo-multilib-sparc64-linux-gnu  # Go compiler (based on GCC) for the sparc64 architecture
sudo apt install -y	gccgo-powerpc-linux-gnu  # Go compiler (based on GCC) for the powerpc architecture
sudo apt install -y	gccgo-powerpc-linux-gnuspe  # Go compiler (based on GCC) for the powerpcspe architecture
sudo apt install -y	gccgo-powerpc64-linux-gnu  # Go compiler (based on GCC) for the ppc64 architecture
sudo apt install -y	gccgo-powerpc64le-linux-gnu  # Go compiler (based on GCC) for the ppc64el architecture
sudo apt install -y	gccgo-s390x-linux-gnu  # Go compiler (based on GCC) for the s390x architecture
sudo apt install -y	gccgo-sparc64-linux-gnu  # Go compiler (based on GCC) for the sparc64 architecture
sudo apt install -y	gdb-mingw-w64  # Cross-debugger for Win32 and Win64 using MinGW-w64
sudo apt install -y	gdb-mingw-w64-target  # Cross-debugger server for Win32 and Win64 using MinGW-w64
sudo apt install -y	gdc  # D compiler (language version 2), based on the GCC backend
sudo apt install -y	gdc-4.8  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-5  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-aarch64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-alpha-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-arm-linux-gnueabi  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-arm-linux-gnueabihf  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-m68k-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-mips-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-mips64-linux-gnuabi64  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-mips64el-linux-gnuabi64  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-mipsel-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-multilib  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-arm-linux-gnueabihf  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-mips-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-mips64-linux-gnuabi64  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-mips64el-linux-gnuabi64  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-mipsel-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-powerpc-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-powerpc64-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-s390x-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-sparc64-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-powerpc-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-powerpc-linux-gnuspe  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-powerpc64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-powerpc64le-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-s390x-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-sh4-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-sparc64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-aarch64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-alpha-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-arm-linux-gnueabi  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-arm-linux-gnueabihf  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-hppa-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-m68k-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-mips-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-mips64-linux-gnuabi64  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-mips64el-linux-gnuabi64  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-mipsel-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-multilib  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-arm-linux-gnueabihf  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-mips-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-mips64-linux-gnuabi64  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-mips64el-linux-gnuabi64  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-mipsel-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-powerpc-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-powerpc64-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-s390x-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-sparc64-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-powerpc-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-powerpc-linux-gnuspe  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-powerpc64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-powerpc64le-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-s390x-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-sh4-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-sparc64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-7  # GNU D compiler (version 2)
sudo apt install -y	gdc-7-multilib  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-aarch64-linux-gnu  # GNU D compiler (based on GCC) for the arm64 architecture
sudo apt install -y	gdc-alpha-linux-gnu  # GNU D compiler (based on GCC) for the alpha architecture
sudo apt install -y	gdc-arm-linux-gnueabi  # GNU D compiler (based on GCC) for the armel architecture
sudo apt install -y	gdc-arm-linux-gnueabihf  # GNU D compiler (based on GCC) for the armhf architecture
sudo apt install -y	gdc-hppa-linux-gnu  # GNU D compiler (based on GCC) for the hppa architecture
sudo apt install -y	gdc-m68k-linux-gnu  # GNU D compiler (based on GCC) for the m68k architecture
sudo apt install -y	gdc-mips-linux-gnu  # GNU D compiler (based on GCC) for the mips architecture
sudo apt install -y	gdc-mips64-linux-gnuabi64  # GNU D compiler (based on GCC) for the mips64 architecture
sudo apt install -y	gdc-mips64el-linux-gnuabi64  # GNU D compiler (based on GCC) for the mips64el architecture
sudo apt install -y	gdc-mipsel-linux-gnu  # GNU D compiler (based on GCC) for the mipsel architecture
sudo apt install -y	gdc-multilib-arm-linux-gnueabihf  # GNU D compiler (based on GCC) for the armhf architecture
sudo apt install -y	gdc-multilib-mips-linux-gnu  # GNU D compiler (based on GCC) for the mips architecture
sudo apt install -y	gdc-multilib-mips64-linux-gnuabi64  # GNU D compiler (based on GCC) for the mips64 architecture
sudo apt install -y	gdc-multilib-mips64el-linux-gnuabi64  # GNU D compiler (based on GCC) for the mips64el architecture
sudo apt install -y	gdc-multilib-mipsel-linux-gnu  # GNU D compiler (based on GCC) for the mipsel architecture
sudo apt install -y	gdc-multilib-powerpc-linux-gnu  # GNU D compiler (based on GCC) for the powerpc architecture
sudo apt install -y	gdc-multilib-powerpc64-linux-gnu  # GNU D compiler (based on GCC) for the ppc64 architecture
sudo apt install -y	gdc-multilib-s390x-linux-gnu  # GNU D compiler (based on GCC) for the s390x architecture
sudo apt install -y	gdc-multilib-sparc64-linux-gnu  # GNU D compiler (based on GCC) for the sparc64 architecture
sudo apt install -y	gdc-powerpc-linux-gnu  # GNU D compiler (based on GCC) for the powerpc architecture
sudo apt install -y	gdc-powerpc-linux-gnuspe  # GNU D compiler (based on GCC) for the powerpcspe architecture
sudo apt install -y	gdc-powerpc64-linux-gnu  # GNU D compiler (based on GCC) for the ppc64 architecture
sudo apt install -y	gdc-powerpc64le-linux-gnu  # GNU D compiler (based on GCC) for the ppc64el architecture
sudo apt install -y	gdc-s390x-linux-gnu  # GNU D compiler (based on GCC) for the s390x architecture
sudo apt install -y	gdc-sh4-linux-gnu  # GNU D compiler (based on GCC) for the sh4 architecture
sudo apt install -y	gdc-sparc64-linux-gnu  # GNU D compiler (based on GCC) for the sparc64 architecture
sudo apt install -y	gfortran-4.8  # GNU Fortran compiler
sudo apt install -y	gfortran-4.8-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5  # GNU Fortran compiler
sudo apt install -y	gfortran-5-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-alpha-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-5-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-5-m68k-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-mips-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-mips64-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-5-mips64el-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-5-mipsel-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-mips-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-mips64-linux-gnuabi64  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-mips64el-linux-gnuabi64  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-mipsel-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-powerpc64-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-s390x-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-sparc64-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-powerpc-linux-gnuspe  # GNU Fortran compiler
sudo apt install -y	gfortran-5-powerpc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-s390x-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-sh4-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-sparc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6  # GNU Fortran compiler
sudo apt install -y	gfortran-6-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-alpha-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-6-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-6-hppa-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-m68k-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-mips-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-mips64-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-6-mips64el-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-6-mipsel-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-mips-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-mips64-linux-gnuabi64  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-mips64el-linux-gnuabi64  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-mipsel-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-powerpc64-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-s390x-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-sparc64-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-powerpc-linux-gnuspe  # GNU Fortran compiler
sudo apt install -y	gfortran-6-powerpc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-s390x-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-sh4-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-sparc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-alpha-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-7-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-7-hppa-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-m68k-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-mips-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-mips64-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-7-mips64el-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-7-mipsel-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-powerpc-linux-gnuspe  # GNU Fortran compiler
sudo apt install -y	gfortran-7-powerpc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-s390x-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-sh4-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-sparc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-aarch64-linux-gnu  # GNU Fortran 95 compiler for the arm64 architecture
sudo apt install -y	gfortran-alpha-linux-gnu  # GNU Fortran 95 compiler for the alpha architecture
sudo apt install -y	gfortran-arm-linux-gnueabi  # GNU Fortran 95 compiler for the armel architecture
sudo apt install -y	gfortran-arm-linux-gnueabihf  # GNU Fortran 95 compiler for the armhf architecture
sudo apt install -y	gfortran-hppa-linux-gnu  # GNU Fortran 95 compiler for the hppa architecture
sudo apt install -y	gfortran-m68k-linux-gnu  # GNU Fortran 95 compiler for the m68k architecture
sudo apt install -y	gfortran-mingw-w64  # GNU Fortran compiler for MinGW-w64
sudo apt install -y	gfortran-mingw-w64-i686  # GNU Fortran compiler for MinGW-w64 targeting Win32
sudo apt install -y	gfortran-mingw-w64-x86-64  # GNU Fortran compiler for MinGW-w64 targeting Win64
sudo apt install -y	gfortran-mips-linux-gnu  # GNU Fortran 95 compiler for the mips architecture
sudo apt install -y	gfortran-mips64-linux-gnuabi64  # GNU Fortran 95 compiler for the mips64 architecture
sudo apt install -y	gfortran-mips64el-linux-gnuabi64  # GNU Fortran 95 compiler for the mips64el architecture
sudo apt install -y	gfortran-mipsel-linux-gnu  # GNU Fortran 95 compiler for the mipsel architecture
sudo apt install -y	gfortran-multilib-arm-linux-gnueabi  # GNU Fortran 95 compiler for the armel architecture
sudo apt install -y	gfortran-multilib-arm-linux-gnueabihf  # GNU Fortran 95 compiler for the armhf architecture
sudo apt install -y	gfortran-multilib-mips-linux-gnu  # GNU Fortran 95 compiler for the mips architecture
sudo apt install -y	gfortran-multilib-mips64-linux-gnuabi64  # GNU Fortran 95 compiler for the mips64 architecture
sudo apt install -y	gfortran-multilib-mips64el-linux-gnuabi64  # GNU Fortran 95 compiler for the mips64el architecture
sudo apt install -y	gfortran-multilib-mipsel-linux-gnu  # GNU Fortran 95 compiler for the mipsel architecture
sudo apt install -y	gfortran-multilib-powerpc-linux-gnu  # GNU Fortran 95 compiler for the powerpc architecture
sudo apt install -y	gfortran-multilib-powerpc64-linux-gnu  # GNU Fortran 95 compiler for the ppc64 architecture
sudo apt install -y	gfortran-multilib-s390x-linux-gnu  # GNU Fortran 95 compiler for the s390x architecture
sudo apt install -y	gfortran-multilib-sparc64-linux-gnu  # GNU Fortran 95 compiler for the sparc64 architecture
sudo apt install -y	gfortran-powerpc-linux-gnu  # GNU Fortran 95 compiler for the powerpc architecture
sudo apt install -y	gfortran-powerpc-linux-gnuspe  # GNU Fortran 95 compiler for the powerpcspe architecture
sudo apt install -y	gfortran-powerpc64-linux-gnu  # GNU Fortran 95 compiler for the ppc64 architecture
sudo apt install -y	gfortran-powerpc64le-linux-gnu  # GNU Fortran 95 compiler for the ppc64el architecture
sudo apt install -y	gfortran-s390x-linux-gnu  # GNU Fortran 95 compiler for the s390x architecture
sudo apt install -y	gfortran-sh4-linux-gnu  # GNU Fortran 95 compiler for the sh4 architecture
sudo apt install -y	gfortran-sparc64-linux-gnu  # GNU Fortran 95 compiler for the sparc64 architecture
sudo apt install -y	ggcov  # Graphical tool for displaying gcov test coverage data
sudo apt install -y	gnat-5  # GNU Ada compiler
sudo apt install -y	gnat-5-aarch64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-alpha-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-arm-linux-gnueabi  # GNU Ada compiler
sudo apt install -y	gnat-5-arm-linux-gnueabihf  # GNU Ada compiler
sudo apt install -y	gnat-5-doc  # GNU Ada compiler (documentation)
sudo apt install -y	gnat-5-m68k-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-mips-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-mips64el-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-5-mipsel-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-powerpc-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-powerpc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-powerpc64le-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-s390x-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-sh4-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-sjlj  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-aarch64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-alpha-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-arm-linux-gnueabi  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-arm-linux-gnueabihf  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-m68k-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-mips-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-mips64el-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-mipsel-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-powerpc-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-powerpc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-powerpc64le-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-s390x-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-sh4-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sjlj-sparc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-5-sparc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6  # GNU Ada compiler
sudo apt install -y	gnat-6-aarch64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-alpha-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-arm-linux-gnueabi  # GNU Ada compiler
sudo apt install -y	gnat-6-arm-linux-gnueabihf  # GNU Ada compiler
sudo apt install -y	gnat-6-doc  # GNU Ada compiler (documentation)
sudo apt install -y	gnat-6-hppa-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-mips-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-mips64el-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-6-mipsel-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-powerpc-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-powerpc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-powerpc64le-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-s390x-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-sh4-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-sjlj  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-aarch64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-alpha-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-arm-linux-gnueabi  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-arm-linux-gnueabihf  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-hppa-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-mips-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-mips64el-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-mipsel-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-powerpc-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-powerpc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-powerpc64le-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-s390x-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-sh4-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sjlj-sparc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-sparc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7  # GNU Ada compiler
sudo apt install -y	gnat-7-aarch64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-alpha-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-arm-linux-gnueabi  # GNU Ada compiler
sudo apt install -y	gnat-7-arm-linux-gnueabihf  # GNU Ada compiler
sudo apt install -y	gnat-7-doc  # GNU Ada compiler (documentation)
sudo apt install -y	gnat-7-hppa-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-m68k-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-mips-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-mips64-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-7-mips64el-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-7-mipsel-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-powerpc-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-powerpc-linux-gnuspe  # GNU Ada compiler
sudo apt install -y	gnat-7-powerpc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-powerpc64le-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-s390x-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-sh4-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-sjlj  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-aarch64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-alpha-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-arm-linux-gnueabi  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-arm-linux-gnueabihf  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-hppa-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-m68k-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-mips-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-mips64-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-mips64el-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-mipsel-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-powerpc-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-powerpc-linux-gnuspe  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-powerpc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-powerpc64le-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-s390x-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-sh4-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-sparc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sparc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-mingw-w64  # GNU Ada compiler for MinGW-w64
sudo apt install -y	gnat-mingw-w64-i686  # GNU Ada compiler for MinGW-w64 targeting Win32
sudo apt install -y	gnat-mingw-w64-x86-64  # GNU Ada compiler for MinGW-w64 targeting Win64
sudo apt install -y	gobjc  # GNU Objective-C compiler
sudo apt install -y	gobjc++  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.8  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.8-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-alpha-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-m68k-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-mips-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-mips64-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-mipsel-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-mips-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-mips64-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-mipsel-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-powerpc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-sparc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-powerpc-linux-gnuspe  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-powerpc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-s390x-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-sh4-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-sparc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-alpha-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-hppa-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-m68k-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-mips-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-mips64-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-mipsel-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-mips-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-mips64-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-mipsel-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-powerpc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-sparc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-powerpc-linux-gnuspe  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-powerpc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-s390x-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-sh4-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-sparc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-alpha-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-hppa-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-m68k-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-mips-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-mips64-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-mipsel-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-mips-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-mips64-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-mipsel-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-powerpc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-sparc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-powerpc-linux-gnuspe  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-powerpc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-s390x-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-sh4-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-sparc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-aarch64-linux-gnu  # GNU Objective-C++ compiler for the arm64 architecture
sudo apt install -y	gobjc++-alpha-linux-gnu  # GNU Objective-C++ compiler for the alpha architecture
sudo apt install -y	gobjc++-arm-linux-gnueabi  # GNU Objective-C++ compiler for the armel architecture
sudo apt install -y	gobjc++-arm-linux-gnueabihf  # GNU Objective-C++ compiler for the armhf architecture
sudo apt install -y	gobjc++-hppa-linux-gnu  # GNU Objective-C++ compiler for the hppa architecture
sudo apt install -y	gobjc++-m68k-linux-gnu  # GNU Objective-C++ compiler for the m68k architecture
sudo apt install -y	gobjc++-mingw-w64  # GNU Objective-C++ compiler for MinGW-w64
sudo apt install -y	gobjc++-mingw-w64-i686  # GNU Objective-C++ compiler for MinGW-w64 targeting Win32
sudo apt install -y	gobjc++-mingw-w64-x86-64  # GNU Objective-C++ compiler for MinGW-w64 targeting Win64
sudo apt install -y	gobjc++-mips-linux-gnu  # GNU Objective-C++ compiler for the mips architecture
sudo apt install -y	gobjc++-mips64-linux-gnuabi64  # GNU Objective-C++ compiler for the mips64 architecture
sudo apt install -y	gobjc++-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler for the mips64el architecture
sudo apt install -y	gobjc++-mipsel-linux-gnu  # GNU Objective-C++ compiler for the mipsel architecture
sudo apt install -y	gobjc++-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler for the armel architecture
sudo apt install -y	gobjc++-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler for the armhf architecture
sudo apt install -y	gobjc++-multilib-mips-linux-gnu  # GNU Objective-C++ compiler for the mips architecture
sudo apt install -y	gobjc++-multilib-mips64-linux-gnuabi64  # GNU Objective-C++ compiler for the mips64 architecture
sudo apt install -y	gobjc++-multilib-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler for the mips64el architecture
sudo apt install -y	gobjc++-multilib-mipsel-linux-gnu  # GNU Objective-C++ compiler for the mipsel architecture
sudo apt install -y	gobjc++-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler for the powerpc architecture
sudo apt install -y	gobjc++-multilib-powerpc64-linux-gnu  # GNU Objective-C++ compiler for the ppc64 architecture
sudo apt install -y	gobjc++-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler for the s390x architecture
sudo apt install -y	gobjc++-multilib-sparc64-linux-gnu  # GNU Objective-C++ compiler for the sparc64 architecture
sudo apt install -y	gobjc++-powerpc-linux-gnu  # GNU Objective-C++ compiler for the powerpc architecture
sudo apt install -y	gobjc++-powerpc-linux-gnuspe  # GNU Objective-C++ compiler for the powerpcspe architecture
sudo apt install -y	gobjc++-powerpc64-linux-gnu  # GNU Objective-C++ compiler for the ppc64 architecture
sudo apt install -y	gobjc++-powerpc64le-linux-gnu  # GNU Objective-C++ compiler for the ppc64el architecture
sudo apt install -y	gobjc++-s390x-linux-gnu  # GNU Objective-C++ compiler for the s390x architecture
sudo apt install -y	gobjc++-sh4-linux-gnu  # GNU Objective-C++ compiler for the sh4 architecture
sudo apt install -y	gobjc++-sparc64-linux-gnu  # GNU Objective-C++ compiler for the sparc64 architecture
sudo apt install -y	gobjc-4.8  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.8-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-alpha-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-m68k-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-mips-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-mips64-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-mips64el-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-mipsel-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-mips-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-mips64-linux-gnuabi64  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-mips64el-linux-gnuabi64  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-mipsel-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-powerpc64-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-s390x-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-sparc64-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-powerpc-linux-gnuspe  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-powerpc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-s390x-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-sh4-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-sparc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-alpha-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-hppa-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-m68k-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-mips-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-mips64-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-mips64el-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-mipsel-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-mips-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-mips64-linux-gnuabi64  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-mips64el-linux-gnuabi64  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-mipsel-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-powerpc64-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-s390x-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-sparc64-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-powerpc-linux-gnuspe  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-powerpc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-s390x-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-sh4-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-sparc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-alpha-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-hppa-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-m68k-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-mips-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-mips64-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-mips64el-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-mipsel-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-7-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-powerpc-linux-gnuspe  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-powerpc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-s390x-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-sh4-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-sparc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-aarch64-linux-gnu  # GNU Objective-C compiler for the arm64 architecture
sudo apt install -y	gobjc-alpha-linux-gnu  # GNU Objective-C compiler for the alpha architecture
sudo apt install -y	gobjc-arm-linux-gnueabi  # GNU Objective-C compiler for the armel architecture
sudo apt install -y	gobjc-arm-linux-gnueabihf  # GNU Objective-C compiler for the armhf architecture
sudo apt install -y	gobjc-hppa-linux-gnu  # GNU Objective-C compiler for the hppa architecture
sudo apt install -y	gobjc-m68k-linux-gnu  # GNU Objective-C compiler for the m68k architecture
sudo apt install -y	gobjc-mingw-w64  # GNU Objective-C compiler for MinGW-w64
sudo apt install -y	gobjc-mingw-w64-i686  # GNU Objective-C compiler for MinGW-w64 targeting Win32
sudo apt install -y	gobjc-mingw-w64-x86-64  # GNU Objective-C compiler for MinGW-w64 targeting Win64
sudo apt install -y	gobjc-mips-linux-gnu  # GNU Objective-C compiler for the mips architecture
sudo apt install -y	gobjc-mips64-linux-gnuabi64  # GNU Objective-C compiler for the mips64 architecture
sudo apt install -y	gobjc-mips64el-linux-gnuabi64  # GNU Objective-C compiler for the mips64el architecture
sudo apt install -y	gobjc-mipsel-linux-gnu  # GNU Objective-C compiler for the mipsel architecture
sudo apt install -y	gobjc-multilib-arm-linux-gnueabi  # GNU Objective-C compiler for the armel architecture
sudo apt install -y	gobjc-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler for the armhf architecture
sudo apt install -y	gobjc-multilib-mips-linux-gnu  # GNU Objective-C compiler for the mips architecture
sudo apt install -y	gobjc-multilib-mips64-linux-gnuabi64  # GNU Objective-C compiler for the mips64 architecture
sudo apt install -y	gobjc-multilib-mips64el-linux-gnuabi64  # GNU Objective-C compiler for the mips64el architecture
sudo apt install -y	gobjc-multilib-mipsel-linux-gnu  # GNU Objective-C compiler for the mipsel architecture
sudo apt install -y	gobjc-multilib-powerpc-linux-gnu  # GNU Objective-C compiler for the powerpc architecture
sudo apt install -y	gobjc-multilib-powerpc64-linux-gnu  # GNU Objective-C compiler for the ppc64 architecture
sudo apt install -y	gobjc-multilib-s390x-linux-gnu  # GNU Objective-C compiler for the s390x architecture
sudo apt install -y	gobjc-multilib-sparc64-linux-gnu  # GNU Objective-C compiler for the sparc64 architecture
sudo apt install -y	gobjc-powerpc-linux-gnu  # GNU Objective-C compiler for the powerpc architecture
sudo apt install -y	gobjc-powerpc-linux-gnuspe  # GNU Objective-C compiler for the powerpcspe architecture
sudo apt install -y	gobjc-powerpc64-linux-gnu  # GNU Objective-C compiler for the ppc64 architecture
sudo apt install -y	gobjc-powerpc64le-linux-gnu  # GNU Objective-C compiler for the ppc64el architecture
sudo apt install -y	gobjc-s390x-linux-gnu  # GNU Objective-C compiler for the s390x architecture
sudo apt install -y	gobjc-sh4-linux-gnu  # GNU Objective-C compiler for the sh4 architecture
sudo apt install -y	gobjc-sparc64-linux-gnu  # GNU Objective-C compiler for the sparc64 architecture
sudo apt install -y	htslib-test  # Test data for HTSlib
sudo apt install -y	inotify-hookable  # blocking command-line interface to inotify
sudo apt install -y	ktap  # lightweight script-based dynamic tracing tool for Linux
sudo apt install -y	lib32atomic1-dbg-mips64-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-dbg-mips64el-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-dbg-ppc64-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-dbg-s390x-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-dbg-sparc64-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-mips64-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-mips64el-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-ppc64-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-s390x-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-sparc64-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32gcc-4.8-dev  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev-mips64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev-mips64el-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev-ppc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev-s390x-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-5-dev-sparc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-mips64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-mips64el-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-ppc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-s390x-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-sparc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-mips64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-mips64el-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-ppc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-s390x-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-sparc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc1-mips64-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-mips64el-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-ppc64-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-s390x-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-sparc64-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gomp1-dbg-mips64-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-dbg-mips64el-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-dbg-ppc64-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-dbg-s390x-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-dbg-sparc64-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-mips64-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-mips64el-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-ppc64-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-s390x-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-sparc64-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib64atomic1-dbg-mips-cross  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64atomic1-dbg-mipsel-cross  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64atomic1-dbg-powerpc-cross  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64atomic1-mips-cross  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64atomic1-mipsel-cross  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64atomic1-powerpc-cross  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64gcc-5-dev-mips-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-5-dev-mipsel-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-5-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-6-dev-mips-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-6-dev-mipsel-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-6-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-7-dev-mips-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-7-dev-mipsel-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-7-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gomp1-dbg-mips-cross  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64gomp1-dbg-mipsel-cross  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64gomp1-dbg-powerpc-cross  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64gomp1-mips-cross  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	lib64gomp1-mipsel-cross  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	lib64gomp1-powerpc-cross  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	libalien-wxwidgets-perl  # Perl module for locating wxWidgets binaries
sudo apt install -y	libatomic1-alpha-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-armel-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-dbg-alpha-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-arm64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-armel-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-armhf-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-hppa-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-m68k-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-mips-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-mips64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-mips64el-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-mipsel-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-powerpc-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-powerpcspe-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-ppc64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-ppc64el-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-s390x-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-sh4-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-sparc64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-hppa-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-m68k-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-mips-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-mips64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-mips64el-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-mipsel-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-powerpcspe-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-ppc64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-s390x-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-sh4-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-sparc64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libclang-3.9-dev  # clang library  # Development package
sudo apt install -y	libclang-common-3.9-dev  # clang library  # Common development package
sudo apt install -y	libclang1-3.9  # C interface to the clang library
sudo apt install -y	libclang1-3.9-dbg  # clang library
sudo apt install -y	libclang1-5.0-dbg  # clang library (debug)
sudo apt install -y	libeigen3-dev  # lightweight C++ template library for linear algebra
sudo apt install -y	libgcc-4.8-dev  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-alpha-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-m68k-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-mips-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-mips64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-mips64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-mipsel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-powerpcspe-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-ppc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-s390x-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-sh4-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-sparc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-alpha-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-hppa-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-m68k-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-mips-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-mips64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-mips64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-mipsel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-powerpcspe-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-ppc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-s390x-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-sh4-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-sparc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-alpha-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-hppa-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-m68k-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-mips-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-mips64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-mips64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-mipsel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-powerpcspe-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-ppc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-s390x-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-sh4-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-sparc64-cross  # GCC support library (development files)
sudo apt install -y	libgnat-5  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-alpha-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-arm64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-armel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-armhf-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-dbg  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-alpha-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-arm64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-armel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-armhf-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-m68k-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-mips-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-mips64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-mipsel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-powerpc-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-ppc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-ppc64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-s390x-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-sh4-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-dbg-sparc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-m68k-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-mips-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-mips64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-mipsel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-powerpc-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-ppc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-ppc64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-s390x-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-sh4-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-5-sparc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-alpha-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-arm64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-armel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-armhf-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-dbg  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-alpha-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-arm64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-armel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-armhf-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-hppa-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-mips-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-mips64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-mipsel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-powerpc-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-ppc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-ppc64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-s390x-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-sh4-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-sparc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-hppa-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-mips-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-mips64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-mipsel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-powerpc-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-ppc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-ppc64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-s390x-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-sh4-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-sparc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-alpha-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-arm64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-armel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-armhf-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-dbg  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-alpha-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-arm64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-armel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-armhf-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-hppa-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-m68k-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-mips-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-mips64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-mips64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-mipsel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-powerpc-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-powerpcspe-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-ppc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-ppc64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-s390x-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-sh4-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-sparc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-hppa-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-m68k-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-mips-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-mips64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-mips64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-mipsel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-powerpc-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-powerpcspe-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-ppc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-ppc64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-s390x-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-sh4-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-sparc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnatprj5  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-alpha-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-arm64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-armel-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-armhf-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-dbg  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-alpha-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-arm64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-armel-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-armhf-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-m68k-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-mips-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-mips64el-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-mipsel-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-powerpc-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-ppc64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-ppc64el-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-s390x-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-sh4-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dbg-sparc64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dev  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-alpha-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-arm64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-armel-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-armhf-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-m68k-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-mips-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-mips64el-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-mipsel-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-powerpc-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-ppc64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-ppc64el-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-s390x-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-sh4-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-dev-sparc64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-m68k-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-mips-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-mips64el-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-mipsel-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-powerpc-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-ppc64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-ppc64el-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-s390x-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-sh4-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj5-sparc64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-alpha-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-arm64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-armel-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-armhf-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-dbg  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-alpha-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-arm64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-armel-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-armhf-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-hppa-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-mips-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-mips64el-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-mipsel-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-powerpc-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-ppc64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-ppc64el-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-s390x-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-sh4-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-sparc64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dev  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-alpha-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-arm64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-armel-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-armhf-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-hppa-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-mips-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-mips64el-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-mipsel-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-powerpc-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-ppc64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-ppc64el-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-s390x-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-sh4-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-sparc64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-hppa-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-mips-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-mips64el-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-mipsel-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-powerpc-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-ppc64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-ppc64el-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-s390x-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-sh4-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-sparc64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatvsn5  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-alpha-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-arm64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-armel-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-armhf-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-dbg  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-alpha-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-arm64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-armel-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-armhf-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-m68k-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-mips-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-mips64el-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-mipsel-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-powerpc-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-ppc64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-ppc64el-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-s390x-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-sh4-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dbg-sparc64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dev  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-alpha-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-arm64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-armel-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-armhf-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-m68k-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-mips-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-mips64el-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-mipsel-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-powerpc-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-ppc64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-ppc64el-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-s390x-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-sh4-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-dev-sparc64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-m68k-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-mips-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-mips64el-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-mipsel-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-powerpc-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-ppc64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-ppc64el-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-s390x-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-sh4-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn5-sparc64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-alpha-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-arm64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-armel-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-armhf-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-dbg  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-alpha-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-arm64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-armel-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-armhf-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-hppa-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-mips-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-mips64el-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-mipsel-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-powerpc-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-ppc64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-ppc64el-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-s390x-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-sh4-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-sparc64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dev  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-alpha-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-arm64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-armel-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-armhf-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-hppa-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-mips-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-mips64el-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-mipsel-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-powerpc-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-ppc64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-ppc64el-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-s390x-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-sh4-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-sparc64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-hppa-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-mips-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-mips64el-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-mipsel-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-powerpc-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-ppc64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-ppc64el-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-s390x-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-sh4-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-sparc64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn7  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn7-dbg  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn7-dev  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgomp1-alpha-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-armel-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-dbg-alpha-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-arm64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-armel-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-armhf-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-hppa-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-m68k-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-mips-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-mips64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-mips64el-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-mipsel-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-powerpc-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-powerpcspe-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-ppc64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-ppc64el-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-s390x-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-sh4-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-sparc64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-hppa-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-m68k-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-mips-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-mips64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-mips64el-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-mipsel-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-powerpcspe-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-ppc64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-s390x-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-sh4-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-sparc64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libhfatomic1-armel-cross  # support library providing __atomic built-in functions (hard float ABI)
sudo apt install -y	libhfatomic1-dbg-armel-cross  # support library providing __atomic built-in functions (hard float ABI debug symbols)
sudo apt install -y	libhfgcc-5-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhfgcc-6-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhfgcc-7-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhfgomp1-armel-cross  # GCC OpenMP (GOMP) support library (hard float ABI)
sudo apt install -y	libhts-dev  # development files for the HTSlib
sudo apt install -y	libhts-private-dev  # private development files for the HTSlib (use with care)
sudo apt install -y	libhts2  # C library for high-throughput sequencing data formats
sudo apt install -y	libjnr-x86asm-java  # Pure java x86 and x86_64 assembler
sudo apt install -y	libn32atomic1-dbg-mips-cross  # support library providing __atomic built-in functions (n32 debug symbols)
sudo apt install -y	libn32atomic1-dbg-mips64-cross  # support library providing __atomic built-in functions (n32 debug symbols)
sudo apt install -y	libn32atomic1-dbg-mips64el-cross  # support library providing __atomic built-in functions (n32 debug symbols)
sudo apt install -y	libn32atomic1-dbg-mipsel-cross  # support library providing __atomic built-in functions (n32 debug symbols)
sudo apt install -y	libn32atomic1-mips-cross  # support library providing __atomic built-in functions (n32)
sudo apt install -y	libn32atomic1-mips64-cross  # support library providing __atomic built-in functions (n32)
sudo apt install -y	libn32atomic1-mips64el-cross  # support library providing __atomic built-in functions (n32)
sudo apt install -y	libn32atomic1-mipsel-cross  # support library providing __atomic built-in functions (n32)
sudo apt install -y	libn32gcc-5-dev-mips-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-5-dev-mips64-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-5-dev-mips64el-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-5-dev-mipsel-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-6-dev-mips-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-6-dev-mips64-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-6-dev-mips64el-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-6-dev-mipsel-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-7-dev-mips-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-7-dev-mips64-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-7-dev-mips64el-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-7-dev-mipsel-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gomp1-mips-cross  # GCC OpenMP (GOMP) support library (n32)
sudo apt install -y	libn32gomp1-mips64-cross  # GCC OpenMP (GOMP) support library (n32)
sudo apt install -y	libn32gomp1-mips64el-cross  # GCC OpenMP (GOMP) support library (n32)
sudo apt install -y	libn32gomp1-mipsel-cross  # GCC OpenMP (GOMP) support library (n32)
sudo apt install -y	librelaxngcc-java  # RELAX NG Compiler Compiler
sudo apt install -y	librelaxngcc-java-doc  # RELAX NG Compiler Compiler -- documentation
sudo apt install -y	libsfatomic1-armhf-cross  # support library providing __atomic built-in functions (soft float ABI)
sudo apt install -y	libsfatomic1-dbg-armhf-cross  # support library providing __atomic built-in functions (soft float ABI debug symbols)
sudo apt install -y	libsfgcc-5-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgcc-6-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgcc-7-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgomp1-armhf-cross  # GCC OpenMP (GOMP) support library (soft float ABI)
sudo apt install -y	libtcc-dev  # fast library for dynamic code generation
sudo apt install -y	libx32gcc-4.8-dev  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-5-dev  # GCC support library (x32 development files)
sudo apt install -y	likwid  # toolsuite for performance oriented programmers
sudo apt install -y	makedepf90  # Fortran-90 dependency processor for Makefiles
sudo apt install -y	mcpp  # Alternative C/C++ preprocessor
sudo apt install -y	mingw-w64  # Development environment targeting 32- and 64-bit Windows
sudo apt install -y	mingw-w64-common  # Common files for Mingw-w64
sudo apt install -y	mingw-w64-i686-dev  # Development files for MinGW-w64 targeting Win32
sudo apt install -y	mingw-w64-tools  # Development tools for 32- and 64-bit Windows
sudo apt install -y	mingw-w64-x86-64-dev  # Development files for MinGW-w64 targeting Win64
sudo apt install -y	msp430mcu  # Spec files, headers and linker scripts for TI's MSP430 targets
sudo apt install -y	musl-tools  # standard C library tools
sudo apt install -y	node-lcov-parse  # Parse lcov results files and return JSON
sudo apt install -y	open-cobol  # COBOL compiler
sudo apt install -y	pentium-builder  # force pentium optimized compilation
sudo apt install -y	python-ck  # Python2 light-weight knowledge manager
sudo apt install -y	python-clang-3.9  # Clang Python Bindings
sudo apt install -y	python-gccjit  # Python bindings for libgccjit
sudo apt install -y	python-gccjit-dbg  # Python bindings for libgccjit (debug build)
sudo apt install -y	python-gccjit-doc  # Python bindings for libgccjit (documentation)
sudo apt install -y	python-pygccxml  # specialized XML reader reads the output from gccxml  # python2 lib
sudo apt install -y	python-pygccxml-doc  # specialized XML reader reads the output from gccxml  # documentation
sudo apt install -y	python3-gccjit  # Python3 bindings for libgccjit
sudo apt install -y	python3-gccjit-dbg  # Python3 bindings for libgccjit (debug build)
sudo apt install -y	python3-pygccxml  # specialized XML reader reads the output from gccxml  # python3 lib
sudo apt install -y	ratfor  # Rational Fortran preprocessor for Fortran 77
sudo apt install -y	snp-sites  # Binary code for the package snp-sites
sudo apt install -y	sparse  # semantic parser of source files
sudo apt install -y	sparse-test-inspect  # semantic parser of source files
sudo apt install -y	stalin  # An extremely aggressive Scheme compiler
sudo apt install -y	sysinfo  # display computer and system information
sudo apt install -y	tcc  # small ANSI C compiler
sudo apt install -y	ubertooth-firmware  # Firmware for Ubertooth
sudo apt install -y	ubertooth-firmware-source  # Source code for the Ubertooth firmware
sudo apt install -y	uisp  # Micro In-System Programmer for Atmel's AVR MCUs
sudo apt install -y	undertaker  # variability-aware tool for static code analysis
sudo apt install -y	uwsgi-plugin-gccgo  # GNU Go plugin for uWSGI
sudo apt install -y	lib64gcc-4.8-dev  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-5-dev  # GCC support library (64bit development files)
sudo apt install -y	clang  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-4.0  # C, C++ and Objective-C compiler
sudo apt install -y	clang-4.0-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-4.0-examples  # Clang examples
sudo apt install -y	clang-5.0  # C, C++ and Objective-C compiler
sudo apt install -y	clang-5.0-examples  # Clang examples
sudo apt install -y	clang-6.0  # C, C++ and Objective-C compiler
sudo apt install -y	clang-6.0-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-6.0-examples  # Clang examples
sudo apt install -y	clang-tools  # clang-based tools
sudo apt install -y	clang-tools-4.0  # clang-based tools for C/C++ developments
sudo apt install -y	clang-tools-5.0  # clang-based tools for C/C++ developments
sudo apt install -y	clang-tools-6.0  # clang-based tools for C/C++ developments
sudo apt install -y	colorized-logs  # tools for consuming logs with ANSI color
sudo apt install -y	cpp-5-i686-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-5-x86-64-linux-gnux32  # GNU C preprocessor
sudo apt install -y	cpp-6-i686-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-6-x86-64-linux-gnux32  # GNU C preprocessor
sudo apt install -y	cpp-7-i686-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-riscv64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-x86-64-linux-gnux32  # GNU C preprocessor
sudo apt install -y	cpp-8  # GNU C preprocessor
sudo apt install -y	cpp-8-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-alpha-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-8-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-8-hppa-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-i686-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-m68k-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-mips-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-mips64-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-8-mips64el-linux-gnuabi64  # GNU C preprocessor
sudo apt install -y	cpp-8-mipsel-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-powerpc-linux-gnuspe  # GNU C preprocessor
sudo apt install -y	cpp-8-powerpc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-riscv64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-s390x-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-sh4-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-sparc64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-x86-64-linux-gnux32  # GNU C preprocessor
sudo apt install -y	cpp-i686-linux-gnu  # GNU C preprocessor (cpp) for the i386 architecture
sudo apt install -y	cpp-riscv64-linux-gnu  # GNU C preprocessor (cpp) for the riscv64 architecture
sudo apt install -y	cpp-x86-64-linux-gnux32  # GNU C preprocessor (cpp) for the x32 architecture
sudo apt install -y	gcc-4.8-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-5-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-5-i686-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-i686-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-5-multilib-i686-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-multilib-x86-64-linux-gnux32  # GNU C compiler (multilib support)
sudo apt install -y	gcc-5-plugin-dev-i686-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-plugin-dev-x86-64-linux-gnux32  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-5-x86-64-linux-gnux32  # GNU C compiler
sudo apt install -y	gcc-5-x86-64-linux-gnux32-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-6-i686-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-i686-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-multilib-i686-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-multilib-x86-64-linux-gnux32  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-plugin-dev-i686-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-plugin-dev-x86-64-linux-gnux32  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-x86-64-linux-gnux32  # GNU C compiler
sudo apt install -y	gcc-6-x86-64-linux-gnux32-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-i686-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-offload-nvptx  # GCC offloading compiler to NVPTX
sudo apt install -y	gcc-7-plugin-dev-i686-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-riscv64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-plugin-dev-x86-64-linux-gnux32  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-riscv64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-x86-64-linux-gnux32-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8  # GNU C compiler
sudo apt install -y	gcc-8-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-alpha-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-cross-base-ports  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	gcc-8-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-8-hppa-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-hppa64-linux-gnu  # GNU C compiler (cross compiler for hppa64)
sudo apt install -y	gcc-8-i686-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-8-m68k-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-mips-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-mips64-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-mips64el-linux-gnuabi64-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-mipsel-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-8-offload-nvptx  # GCC offloading compiler to NVPTX
sudo apt install -y	gcc-8-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-aarch64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-alpha-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-arm-linux-gnueabi  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-arm-linux-gnueabihf  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-hppa-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-i686-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-m68k-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-mips-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-mips64-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-mips64el-linux-gnuabi64  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-mipsel-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-powerpc-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-powerpc-linux-gnuspe  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-powerpc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-powerpc64le-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-riscv64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-s390x-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-sh4-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-sparc64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-plugin-dev-x86-64-linux-gnux32  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-powerpc-linux-gnuspe-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-powerpc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-riscv64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-s390x-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-sh4-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-8-sparc64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-test-results  # Test results for the GCC test suite
sudo apt install -y	gcc-8-x86-64-linux-gnux32-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-i686-linux-gnu  # GNU C compiler for the i386 architecture
sudo apt install -y	gcc-multilib-i686-linux-gnu  # GNU C compiler for the i386 architecture
sudo apt install -y	gcc-multilib-x86-64-linux-gnux32  # GNU C compiler for the x32 architecture
sudo apt install -y	gcc-offload-nvptx  # GCC offloading compiler to NVPTX
sudo apt install -y	gcc-opt  # allow global optimization flags for gcc, g++
sudo apt install -y	gcc-python3-dbg-plugin  # plugin for GCC to invoke Python scripts from inside the compiler
sudo apt install -y	gcc-python3-plugin  # plugin for GCC to invoke Python scripts from inside the compiler
sudo apt install -y	gcc-riscv64-linux-gnu  # GNU C compiler for the riscv64 architecture
sudo apt install -y	gcc-x86-64-linux-gnux32  # GNU C compiler for the x32 architecture
sudo apt install -y	gccbrig  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-7  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-7-i686-linux-gnu  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-7-x86-64-linux-gnux32  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-8  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-8-i686-linux-gnu  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-8-x86-64-linux-gnux32  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccgo-4.8-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-5-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-5-i686-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-5-multilib-i686-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-multilib-x86-64-linux-gnux32  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-5-x86-64-linux-gnux32  # GNU Go compiler
sudo apt install -y	gccgo-6-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-6-i686-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-6-multilib-i686-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-multilib-x86-64-linux-gnux32  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-x86-64-linux-gnux32  # GNU Go compiler
sudo apt install -y	gccgo-7-i686-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-m68k-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-x86-64-linux-gnux32  # GNU Go compiler
sudo apt install -y	gccgo-8  # GNU Go compiler
sudo apt install -y	gccgo-8-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-alpha-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-8-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-8-i686-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-mips-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-mips64-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-8-mips64el-linux-gnuabi64  # GNU Go compiler
sudo apt install -y	gccgo-8-mipsel-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-8-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-powerpc-linux-gnuspe  # GNU Go compiler
sudo apt install -y	gccgo-8-powerpc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-riscv64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-s390x-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-sparc64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-x86-64-linux-gnux32  # GNU Go compiler
sudo apt install -y	gccgo-i686-linux-gnu  # Go compiler (based on GCC) for the i386 architecture
sudo apt install -y	gccgo-multilib-i686-linux-gnu  # Go compiler (based on GCC) for the i386 architecture
sudo apt install -y	gccgo-multilib-x86-64-linux-gnux32  # Go compiler (based on GCC) for the x32 architecture
sudo apt install -y	gccgo-riscv64-linux-gnu  # Go compiler (based on GCC) for the riscv64 architecture
sudo apt install -y	gccgo-x86-64-linux-gnux32  # Go compiler (based on GCC) for the x32 architecture
sudo apt install -y	gccintro  # Introduction to GCC by Brian J. Gough
sudo apt install -y	gdc-5-i686-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-5-multilib-i686-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-multilib-x86-64-linux-gnux32  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-5-x86-64-linux-gnux32  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-i686-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-6-multilib-i686-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-multilib-x86-64-linux-gnux32  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-x86-64-linux-gnux32  # GNU D compiler (version 2)
sudo apt install -y	gdc-8  # GNU D compiler (version 2)
sudo apt install -y	gdc-8-multilib  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-i686-linux-gnu  # GNU D compiler (based on GCC) for the i386 architecture
sudo apt install -y	gdc-multilib-i686-linux-gnu  # GNU D compiler (based on GCC) for the i386 architecture
sudo apt install -y	gdc-multilib-x86-64-linux-gnux32  # GNU D compiler (based on GCC) for the x32 architecture
sudo apt install -y	gdc-riscv64-linux-gnu  # GNU D compiler (based on GCC) for the riscv64 architecture
sudo apt install -y	gdc-x86-64-linux-gnux32  # GNU D compiler (based on GCC) for the x32 architecture
sudo apt install -y	gfortran-5-i686-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-5-multilib-i686-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-multilib-x86-64-linux-gnux32  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-x86-64-linux-gnux32  # GNU Fortran compiler
sudo apt install -y	gfortran-6-i686-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-6-multilib-i686-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-multilib-x86-64-linux-gnux32  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-x86-64-linux-gnux32  # GNU Fortran compiler
sudo apt install -y	gfortran-7-i686-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-riscv64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-x86-64-linux-gnux32  # GNU Fortran compiler
sudo apt install -y	gfortran-8  # GNU Fortran compiler
sudo apt install -y	gfortran-8-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-alpha-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-8-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-8-hppa-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-i686-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-m68k-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-mips-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-mips64-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-8-mips64el-linux-gnuabi64  # GNU Fortran compiler
sudo apt install -y	gfortran-8-mipsel-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-8-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-powerpc-linux-gnuspe  # GNU Fortran compiler
sudo apt install -y	gfortran-8-powerpc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-riscv64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-s390x-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-sh4-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-sparc64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-x86-64-linux-gnux32  # GNU Fortran compiler
sudo apt install -y	gfortran-i686-linux-gnu  # GNU Fortran 95 compiler for the i386 architecture
sudo apt install -y	gfortran-multilib-i686-linux-gnu  # GNU Fortran 95 compiler for the i386 architecture
sudo apt install -y	gfortran-multilib-x86-64-linux-gnux32  # GNU Fortran 95 compiler for the x32 architecture
sudo apt install -y	gfortran-riscv64-linux-gnu  # GNU Fortran 95 compiler for the riscv64 architecture
sudo apt install -y	gfortran-x86-64-linux-gnux32  # GNU Fortran 95 compiler for the x32 architecture
sudo apt install -y	gnat-5-i686-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-sjlj-i686-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-6-i686-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-6-sjlj-i686-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-i686-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-7-sjlj-i686-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-sjlj-x86-64-linux-gnux32  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-x86-64-linux-gnux32  # GNU Ada compiler
sudo apt install -y	gnat-8  # GNU Ada compiler
sudo apt install -y	gnat-8-aarch64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-alpha-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-arm-linux-gnueabi  # GNU Ada compiler
sudo apt install -y	gnat-8-arm-linux-gnueabihf  # GNU Ada compiler
sudo apt install -y	gnat-8-doc  # GNU Ada compiler (documentation)
sudo apt install -y	gnat-8-hppa-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-i686-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-m68k-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-mips-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-mips64-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-8-mips64el-linux-gnuabi64  # GNU Ada compiler
sudo apt install -y	gnat-8-mipsel-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-powerpc-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-powerpc-linux-gnuspe  # GNU Ada compiler
sudo apt install -y	gnat-8-powerpc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-powerpc64le-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-s390x-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-sh4-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-sjlj  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-aarch64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-alpha-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-arm-linux-gnueabi  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-arm-linux-gnueabihf  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-hppa-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-i686-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-m68k-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-mips-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-mips64-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-mips64el-linux-gnuabi64  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-mipsel-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-powerpc-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-powerpc-linux-gnuspe  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-powerpc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-powerpc64le-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-s390x-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-sh4-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-sparc64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sjlj-x86-64-linux-gnux32  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-sparc64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-x86-64-linux-gnux32  # GNU Ada compiler
sudo apt install -y	gobjc++-5-i686-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-5-multilib-i686-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-multilib-x86-64-linux-gnux32  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-x86-64-linux-gnux32  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-i686-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-6-multilib-i686-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-multilib-x86-64-linux-gnux32  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-x86-64-linux-gnux32  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-i686-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-multilib-i686-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-multilib-x86-64-linux-gnux32  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-riscv64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-x86-64-linux-gnux32  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-alpha-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-hppa-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-i686-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-m68k-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-mips-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-mips64-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-mipsel-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-i686-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-mips-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-mips64-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-mips64el-linux-gnuabi64  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-mipsel-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-powerpc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-sparc64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-multilib-x86-64-linux-gnux32  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-powerpc-linux-gnuspe  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-powerpc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-riscv64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-s390x-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-sh4-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-sparc64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-x86-64-linux-gnux32  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-i686-linux-gnu  # GNU Objective-C++ compiler for the i386 architecture
sudo apt install -y	gobjc++-multilib  # GNU Objective-C++ compiler (multilib files)
sudo apt install -y	gobjc++-multilib-i686-linux-gnu  # GNU Objective-C++ compiler for the i386 architecture
sudo apt install -y	gobjc++-multilib-x86-64-linux-gnux32  # GNU Objective-C++ compiler for the x32 architecture
sudo apt install -y	gobjc++-riscv64-linux-gnu  # GNU Objective-C++ compiler for the riscv64 architecture
sudo apt install -y	gobjc++-x86-64-linux-gnux32  # GNU Objective-C++ compiler for the x32 architecture
sudo apt install -y	gobjc-5-i686-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-5-multilib-i686-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-multilib-x86-64-linux-gnux32  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-x86-64-linux-gnux32  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-i686-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-6-multilib-i686-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-multilib-x86-64-linux-gnux32  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-x86-64-linux-gnux32  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-i686-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-riscv64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-x86-64-linux-gnux32  # GNU Objective-C compiler
sudo apt install -y	gobjc-8  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-alpha-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-hppa-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-i686-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-m68k-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-mips-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-mips64-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-mips64el-linux-gnuabi64  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-mipsel-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-8-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-powerpc-linux-gnuspe  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-powerpc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-riscv64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-s390x-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-sh4-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-sparc64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-x86-64-linux-gnux32  # GNU Objective-C compiler
sudo apt install -y	gobjc-i686-linux-gnu  # GNU Objective-C compiler for the i386 architecture
sudo apt install -y	gobjc-multilib  # GNU Objective-C compiler (multilib files)
sudo apt install -y	gobjc-multilib-i686-linux-gnu  # GNU Objective-C compiler for the i386 architecture
sudo apt install -y	gobjc-multilib-x86-64-linux-gnux32  # GNU Objective-C compiler for the x32 architecture
sudo apt install -y	gobjc-riscv64-linux-gnu  # GNU Objective-C compiler for the riscv64 architecture
sudo apt install -y	gobjc-x86-64-linux-gnux32  # GNU Objective-C compiler for the x32 architecture
sudo apt install -y	lib32atomic1-amd64-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32atomic1-dbg-amd64-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-dbg-x32-cross  # support library providing __atomic built-in functions (32 bit debug symbols)
sudo apt install -y	lib32atomic1-x32-cross  # support library providing __atomic built-in functions (32bit)
sudo apt install -y	lib32gcc-5-dev-x32-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-amd64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-6-dev-x32-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-amd64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-7-dev-x32-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-amd64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-mips64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-mips64el-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-ppc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-s390x-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-sparc64-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-8-dev-x32-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc1-amd64-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gcc1-x32-cross  # GCC support library (32 bit Version)
sudo apt install -y	lib32gomp1-amd64-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32gomp1-dbg-amd64-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-dbg-x32-cross  # GCC OpenMP (GOMP) support library (32 bit debug symbols)
sudo apt install -y	lib32gomp1-x32-cross  # GCC OpenMP (GOMP) support library (32bit)
sudo apt install -y	lib32quadmath0-amd64-cross  # GCC Quad-Precision Math Library (32bit)
sudo apt install -y	lib32quadmath0-dbg-amd64-cross  # GCC Quad-Precision Math Library (32 bit debug symbols)
sudo apt install -y	lib32quadmath0-dbg-x32-cross  # GCC Quad-Precision Math Library (32 bit debug symbols)
sudo apt install -y	lib32quadmath0-x32-cross  # GCC Quad-Precision Math Library (32bit)
sudo apt install -y	lib64atomic1-dbg-i386-cross  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64atomic1-dbg-x32-cross  # support library providing __atomic built-in functions (64bit debug symbols)
sudo apt install -y	lib64atomic1-i386-cross  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64atomic1-x32-cross  # support library providing __atomic built-in functions (64bit)
sudo apt install -y	lib64gcc-5-dev-i386-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-5-dev-x32-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-6-dev-i386-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-6-dev-x32-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-7-dev-i386-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-7-dev-x32-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-8-dev-i386-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-8-dev-mips-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-8-dev-mipsel-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-8-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-8-dev-x32-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gomp1-dbg-i386-cross  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64gomp1-dbg-x32-cross  # GCC OpenMP (GOMP) support library (64bit debug symbols)
sudo apt install -y	lib64gomp1-i386-cross  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	lib64gomp1-x32-cross  # GCC OpenMP (GOMP) support library (64bit)
sudo apt install -y	lib64quadmath0-dbg-i386-cross  # GCC Quad-Precision Math Library  (64bit debug symbols)
sudo apt install -y	lib64quadmath0-dbg-x32-cross  # GCC Quad-Precision Math Library  (64bit debug symbols)
sudo apt install -y	lib64quadmath0-i386-cross  # GCC Quad-Precision Math Library  (64bit)
sudo apt install -y	lib64quadmath0-x32-cross  # GCC Quad-Precision Math Library  (64bit)
sudo apt install -y	libatomic1-amd64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-dbg-amd64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-i386-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-riscv64-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-dbg-x32-cross  # support library providing __atomic built-in functions (debug symbols)
sudo apt install -y	libatomic1-i386-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-riscv64-cross  # support library providing __atomic built-in functions
sudo apt install -y	libatomic1-x32-cross  # support library providing __atomic built-in functions
sudo apt install -y	libc++-dev  # LLVM C++ Standard library (development files)
sudo apt install -y	libc++-helpers  # LLVM C++ Standard library  # build helpers
sudo apt install -y	libc++-test  # LLVM C++ Standard library (test cases)
sudo apt install -y	libc++1  # LLVM C++ Standard library
sudo apt install -y	libclang-4.0-dev  # clang library  # Development package
sudo apt install -y	libclang-5.0-dev  # clang library  # Development package
sudo apt install -y	libclang-6.0-dev  # clang library  # Development package
sudo apt install -y	libclang-common-4.0-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-5.0-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-6.0-dev  # clang library  # Common development package
sudo apt install -y	libclang-dev  # clang library  # Development package
sudo apt install -y	libclang1  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	libclang1-4.0  # C interface to the clang library
sudo apt install -y	libclang1-4.0-dbg  # clang library (debug)
sudo apt install -y	libclang1-5.0  # C interface to the clang library
sudo apt install -y	libclang1-6.0-dbg  # clang library (debug)
sudo apt install -y	libcommons-cli-java  # Command line arguments and options parsing library
sudo apt install -y	libgcc-5-dev-i386-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-x32-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-amd64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-i386-cross  # GCC support library (development files)
sudo apt install -y	libgcc-6-dev-x32-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-amd64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-i386-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-riscv64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-7-dev-x32-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-alpha-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-amd64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-hppa-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-i386-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-m68k-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-mips-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-mips64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-mips64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-mipsel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-powerpcspe-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-ppc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-riscv64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-s390x-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-sh4-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-sparc64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-8-dev-x32-cross  # GCC support library (development files)
sudo apt install -y	libgccjit-5-dev  # GCC just-in-time compilation (development files)
sudo apt install -y	libgccjit-5-doc  # GCC just-in-time compilation (documentation)
sudo apt install -y	libgccjit-8-doc  # GCC just-in-time compilation (documentation)
sudo apt install -y	libgnat-5-dbg-i386-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-i386-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-amd64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-6-dbg-amd64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-dbg-i386-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-6-i386-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-amd64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-dbg-amd64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-i386-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-dbg-x32-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-7-i386-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-7-x32-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-alpha-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-amd64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-arm64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-armel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-armhf-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-dbg  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-alpha-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-amd64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-arm64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-armel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-armhf-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-hppa-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-i386-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-m68k-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-mips-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-mips64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-mips64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-mipsel-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-powerpc-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-powerpcspe-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-ppc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-ppc64el-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-s390x-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-sh4-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-sparc64-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-dbg-x32-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-8-hppa-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-i386-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-m68k-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-mips-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-mips64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-mips64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-mipsel-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-powerpc-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-powerpcspe-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-ppc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-ppc64el-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-s390x-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-sh4-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-sparc64-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-8-x32-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnatprj5-dbg-i386-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dev-i386-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-i386-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-amd64-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj6-dbg-amd64-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dbg-i386-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj6-dev-amd64-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-dev-i386-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj6-i386-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatvsn5-dbg-i386-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dev-i386-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-i386-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-amd64-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn6-dbg-amd64-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dbg-i386-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn6-dev-amd64-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-dev-i386-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn6-i386-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn8  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn8-dbg  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn8-dev  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgomp-plugin-nvptx1  # GCC OpenMP v4.5 plugin for offloading to NVPTX
sudo apt install -y	libgomp1-amd64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-dbg-amd64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-i386-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-riscv64-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-dbg-x32-cross  # GCC OpenMP (GOMP) support library (debug symbols)
sudo apt install -y	libgomp1-i386-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-riscv64-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libgomp1-x32-cross  # GCC OpenMP (GOMP) support library
sudo apt install -y	libhfgcc-8-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhfgomp1-dbg-armel-cross  # GCC OpenMP (GOMP) support library (hard float ABI debug symbols)
sudo apt install -y	libn32gcc-8-dev-mips-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-8-dev-mips64-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-8-dev-mips64el-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gcc-8-dev-mipsel-cross  # GCC support library (n32 development files)
sudo apt install -y	libn32gomp1-dbg-mips-cross  # GCC OpenMP (GOMP) support library (n32 debug symbols)
sudo apt install -y	libn32gomp1-dbg-mips64-cross  # GCC OpenMP (GOMP) support library (n32 debug symbols)
sudo apt install -y	libn32gomp1-dbg-mips64el-cross  # GCC OpenMP (GOMP) support library (n32 debug symbols)
sudo apt install -y	libn32gomp1-dbg-mipsel-cross  # GCC OpenMP (GOMP) support library (n32 debug symbols)
sudo apt install -y	libquadmath0-amd64-cross  # GCC Quad-Precision Math Library
sudo apt install -y	libquadmath0-dbg-amd64-cross  # GCC Quad-Precision Math Library (debug symbols)
sudo apt install -y	libquadmath0-dbg-i386-cross  # GCC Quad-Precision Math Library (debug symbols)
sudo apt install -y	libquadmath0-dbg-ppc64el-cross  # GCC Quad-Precision Math Library (debug symbols)
sudo apt install -y	libquadmath0-dbg-x32-cross  # GCC Quad-Precision Math Library (debug symbols)
sudo apt install -y	libquadmath0-i386-cross  # GCC Quad-Precision Math Library
sudo apt install -y	libquadmath0-ppc64el-cross  # GCC Quad-Precision Math Library
sudo apt install -y	libquadmath0-x32-cross  # GCC Quad-Precision Math Library
sudo apt install -y	libscythestat-dev  # header files for Scythe statistics library
sudo apt install -y	libsfgcc-8-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgomp1-dbg-armhf-cross  # GCC OpenMP (GOMP) support library (soft float ABI debug symbols)
sudo apt install -y	libx32atomic1-amd64-cross  # support library providing __atomic built-in functions (x32)
sudo apt install -y	libx32atomic1-dbg-amd64-cross  # support library providing __atomic built-in functions (x32 debug symbols)
sudo apt install -y	libx32atomic1-dbg-i386-cross  # support library providing __atomic built-in functions (x32 debug symbols)
sudo apt install -y	libx32atomic1-i386-cross  # support library providing __atomic built-in functions (x32)
sudo apt install -y	libx32gcc-5-dev-i386-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-6-dev-amd64-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-6-dev-i386-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-7-dev-amd64-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-7-dev-i386-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-8-dev-amd64-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gcc-8-dev-i386-cross  # GCC support library (x32 development files)
sudo apt install -y	libx32gomp1-amd64-cross  # GCC OpenMP (GOMP) support library (x32)
sudo apt install -y	libx32gomp1-dbg-amd64-cross  # GCC OpenMP (GOMP) support library (x32 debug symbols)
sudo apt install -y	libx32gomp1-dbg-i386-cross  # GCC OpenMP (GOMP) support library (x32 debug symbols)
sudo apt install -y	libx32gomp1-i386-cross  # GCC OpenMP (GOMP) support library (x32)
sudo apt install -y	libx32quadmath0-amd64-cross  # GCC Quad-Precision Math Library (x32)
sudo apt install -y	libx32quadmath0-dbg-amd64-cross  # GCC Quad-Precision Math Library (x32 debug symbols)
sudo apt install -y	libx32quadmath0-dbg-i386-cross  # GCC Quad-Precision Math Library (x32 debug symbols)
sudo apt install -y	libx32quadmath0-i386-cross  # GCC Quad-Precision Math Library (x32)
sudo apt install -y	linuxbrew-wrapper  # Homebrew package manager for Linux
sudo apt install -y	nvptx-tools  # collection of tools for use with nvptx-none GCC toolchains
sudo apt install -y	nxt-firmware  # Improved firmware for LEGO Mindstorms NXT bricks
sudo apt install -y	python-clang-4.0  # Clang Python Bindings
sudo apt install -y	python-clang-5.0  # Clang Python Bindings
sudo apt install -y	python-clang-6.0  # Clang Python Bindings
sudo apt install -y	python3-ck  # Python3 light-weight knowledge manager
sudo apt install -y	cpp-6-x86-64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-7-x86-64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-8-x86-64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-x86-64-linux-gnu  # GNU C preprocessor (cpp) for the amd64 architecture
sudo apt install -y	gcc-6-multilib-x86-64-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-6-plugin-dev-x86-64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-6-x86-64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-6-x86-64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-7-plugin-dev-x86-64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-x86-64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-8-plugin-dev-x86-64-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-8-x86-64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-multilib-x86-64-linux-gnu  # GNU C compiler for the amd64 architecture
sudo apt install -y	gcc-x86-64-linux-gnu  # GNU C compiler for the amd64 architecture
sudo apt install -y	gccbrig-7-x86-64-linux-gnu  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccbrig-8-x86-64-linux-gnu  # GNU BRIG (HSA IL) frontend
sudo apt install -y	gccgo-6-multilib-x86-64-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-6-x86-64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-7-x86-64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-8-x86-64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-multilib-x86-64-linux-gnu  # Go compiler (based on GCC) for the amd64 architecture
sudo apt install -y	gccgo-x86-64-linux-gnu  # Go compiler (based on GCC) for the amd64 architecture
sudo apt install -y	gdc-6-multilib-x86-64-linux-gnu  # GNU D compiler (version 2, multilib support)
sudo apt install -y	gdc-6-x86-64-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gdc-multilib-x86-64-linux-gnu  # GNU D compiler (based on GCC) for the amd64 architecture
sudo apt install -y	gdc-x86-64-linux-gnu  # GNU D compiler (based on GCC) for the amd64 architecture
sudo apt install -y	gfortran-6-multilib-x86-64-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-6-x86-64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-7-x86-64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-8-x86-64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-multilib-x86-64-linux-gnu  # GNU Fortran 95 compiler for the amd64 architecture
sudo apt install -y	gfortran-x86-64-linux-gnu  # GNU Fortran 95 compiler for the amd64 architecture
sudo apt install -y	gnat-7-sjlj-x86-64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-7-x86-64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-8-sjlj-x86-64-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-8-x86-64-linux-gnu  # GNU Ada compiler
sudo apt install -y	gobjc++-6-multilib-x86-64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-6-x86-64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-7-multilib-x86-64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-7-x86-64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-8-multilib-x86-64-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-8-x86-64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-multilib-x86-64-linux-gnu  # GNU Objective-C++ compiler for the amd64 architecture
sudo apt install -y	gobjc++-x86-64-linux-gnu  # GNU Objective-C++ compiler for the amd64 architecture
sudo apt install -y	gobjc-6-multilib-x86-64-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-6-x86-64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-7-x86-64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-8-x86-64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-multilib-x86-64-linux-gnu  # GNU Objective-C compiler for the amd64 architecture
sudo apt install -y	gobjc-x86-64-linux-gnu  # GNU Objective-C compiler for the amd64 architecture
sudo apt install -y	tiemu  # Texas Instruments calculators emulator (without GDB)
sudo apt install -y	gcc-7-aarch64-linux-gnu  # GNU C compiler (cross compiler for arm64 architecture)
sudo apt install -y	gcc-7-arm-linux-gnueabihf  # GNU C compiler (cross compiler for armhf architecture)
sudo apt install -y	gcc-7-powerpc-linux-gnu  # GNU C compiler (cross compiler for powerpc architecture)
sudo apt install -y	gcc-7-powerpc64le-linux-gnu  # GNU C compiler (cross compiler for ppc64el architecture)
sudo apt install -y	libclang1-7  # C interface to the clang library
sudo apt install -y	libgcc1-arm64-cross  # GCC support library (arm64)
sudo apt install -y	libgcc1-armhf-cross  # GCC support library (armhf)
sudo apt install -y	libgcc1-powerpc-cross  # GCC support library (powerpc)
sudo apt install -y	libgcc1-ppc64el-cross  # GCC support library (ppc64el)
sudo apt install -y	clang-10  # C, C++ and Objective-C compiler
sudo apt install -y	clang-10-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-10-examples  # Clang examples
sudo apt install -y	clang-7  # C, C++ and Objective-C compiler
sudo apt install -y	clang-7-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-7-examples  # Clang examples
sudo apt install -y	clang-8  # C, C++ and Objective-C compiler
sudo apt install -y	clang-8-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-8-examples  # Clang examples
sudo apt install -y	clang-9  # C, C++ and Objective-C compiler
sudo apt install -y	clang-9-doc  # C, C++ and Objective-C compiler  # Documentation
sudo apt install -y	clang-9-examples  # Clang examples
sudo apt install -y	clang-tools-10  # clang-based tools for C/C++ developments
sudo apt install -y	clang-tools-7  # clang-based tools for C/C++ developments
sudo apt install -y	clang-tools-8  # clang-based tools for C/C++ developments
sudo apt install -y	clang-tools-9  # clang-based tools for C/C++ developments
sudo apt install -y	gcc-7-alpha-linux-gnu  # GNU C compiler (cross compiler for alpha architecture)
sudo apt install -y	gcc-7-arm-linux-gnueabi  # GNU C compiler (cross compiler for armel architecture)
sudo apt install -y	gcc-7-hppa-linux-gnu  # GNU C compiler (cross compiler for hppa architecture)
sudo apt install -y	gcc-7-i686-linux-gnu  # GNU C compiler (cross compiler for i386 architecture)
sudo apt install -y	gcc-7-m68k-linux-gnu  # GNU C compiler (cross compiler for m68k architecture)
sudo apt install -y	gcc-7-mips-linux-gnu  # GNU C compiler (cross compiler for mips architecture)
sudo apt install -y	gcc-7-mips64-linux-gnuabi64  # GNU C compiler (cross compiler for mips64 architecture)
sudo apt install -y	gcc-7-mips64el-linux-gnuabi64  # GNU C compiler (cross compiler for mips64el architecture)
sudo apt install -y	gcc-7-mipsel-linux-gnu  # GNU C compiler (cross compiler for mipsel architecture)
sudo apt install -y	gcc-7-multilib-arm-linux-gnueabi  # GNU C compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gcc-7-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gcc-7-multilib-i686-linux-gnu  # GNU C compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gcc-7-multilib-mips-linux-gnu  # GNU C compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gcc-7-multilib-mips64-linux-gnuabi64  # GNU C compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gcc-7-multilib-mips64el-linux-gnuabi64  # GNU C compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gcc-7-multilib-mipsel-linux-gnu  # GNU C compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gcc-7-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gcc-7-multilib-powerpc64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gcc-7-multilib-s390x-linux-gnu  # GNU C compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gcc-7-multilib-sparc64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gcc-7-multilib-x86-64-linux-gnux32  # GNU C compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gcc-7-powerpc-linux-gnuspe  # GNU C compiler (cross compiler for powerpcspe architecture)
sudo apt install -y	gcc-7-powerpc64-linux-gnu  # GNU C compiler (cross compiler for ppc64 architecture)
sudo apt install -y	gcc-7-riscv64-linux-gnu  # GNU C compiler (cross compiler for riscv64 architecture)
sudo apt install -y	gcc-7-s390x-linux-gnu  # GNU C compiler (cross compiler for s390x architecture)
sudo apt install -y	gcc-7-sh4-linux-gnu  # GNU C compiler (cross compiler for sh4 architecture)
sudo apt install -y	gcc-7-sparc64-linux-gnu  # GNU C compiler (cross compiler for sparc64 architecture)
sudo apt install -y	gcc-7-x86-64-linux-gnux32  # GNU C compiler (cross compiler for x32 architecture)
sudo apt install -y	gcc-8-aarch64-linux-gnu  # GNU C compiler (cross compiler for arm64 architecture)
sudo apt install -y	gcc-8-alpha-linux-gnu  # GNU C compiler (cross compiler for alpha architecture)
sudo apt install -y	gcc-8-arm-linux-gnueabi  # GNU C compiler (cross compiler for armel architecture)
sudo apt install -y	gcc-8-arm-linux-gnueabihf  # GNU C compiler (cross compiler for armhf architecture)
sudo apt install -y	gcc-8-hppa-linux-gnu  # GNU C compiler (cross compiler for hppa architecture)
sudo apt install -y	gcc-8-i686-linux-gnu  # GNU C compiler (cross compiler for i386 architecture)
sudo apt install -y	gcc-8-m68k-linux-gnu  # GNU C compiler (cross compiler for m68k architecture)
sudo apt install -y	gcc-8-mips-linux-gnu  # GNU C compiler (cross compiler for mips architecture)
sudo apt install -y	gcc-8-mips64-linux-gnuabi64  # GNU C compiler (cross compiler for mips64 architecture)
sudo apt install -y	gcc-8-mips64el-linux-gnuabi64  # GNU C compiler (cross compiler for mips64el architecture)
sudo apt install -y	gcc-8-mipsel-linux-gnu  # GNU C compiler (cross compiler for mipsel architecture)
sudo apt install -y	gcc-8-multilib-arm-linux-gnueabi  # GNU C compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gcc-8-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gcc-8-multilib-i686-linux-gnu  # GNU C compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gcc-8-multilib-mips-linux-gnu  # GNU C compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gcc-8-multilib-mips64-linux-gnuabi64  # GNU C compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gcc-8-multilib-mips64el-linux-gnuabi64  # GNU C compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gcc-8-multilib-mipsel-linux-gnu  # GNU C compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gcc-8-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gcc-8-multilib-powerpc64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gcc-8-multilib-s390x-linux-gnu  # GNU C compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gcc-8-multilib-sparc64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gcc-8-multilib-x86-64-linux-gnux32  # GNU C compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gcc-8-powerpc-linux-gnu  # GNU C compiler (cross compiler for powerpc architecture)
sudo apt install -y	gcc-8-powerpc-linux-gnuspe  # GNU C compiler (cross compiler for powerpcspe architecture)
sudo apt install -y	gcc-8-powerpc64-linux-gnu  # GNU C compiler (cross compiler for ppc64 architecture)
sudo apt install -y	gcc-8-powerpc64le-linux-gnu  # GNU C compiler (cross compiler for ppc64el architecture)
sudo apt install -y	gcc-8-riscv64-linux-gnu  # GNU C compiler (cross compiler for riscv64 architecture)
sudo apt install -y	gcc-8-s390x-linux-gnu  # GNU C compiler (cross compiler for s390x architecture)
sudo apt install -y	gcc-8-sh4-linux-gnu  # GNU C compiler (cross compiler for sh4 architecture)
sudo apt install -y	gcc-8-sparc64-linux-gnu  # GNU C compiler (cross compiler for sparc64 architecture)
sudo apt install -y	gcc-8-x86-64-linux-gnux32  # GNU C compiler (cross compiler for x32 architecture)
sudo apt install -y	gccgo-7-multilib-i686-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gccgo-7-multilib-mips-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gccgo-7-multilib-mips64-linux-gnuabi64  # GNU Go compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gccgo-7-multilib-mips64el-linux-gnuabi64  # GNU Go compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gccgo-7-multilib-mipsel-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gccgo-7-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gccgo-7-multilib-powerpc64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gccgo-7-multilib-s390x-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gccgo-7-multilib-sparc64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gccgo-7-multilib-x86-64-linux-gnux32  # GNU Go compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gccgo-8-multilib-i686-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gccgo-8-multilib-mips-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gccgo-8-multilib-mips64-linux-gnuabi64  # GNU Go compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gccgo-8-multilib-mips64el-linux-gnuabi64  # GNU Go compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gccgo-8-multilib-mipsel-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gccgo-8-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gccgo-8-multilib-powerpc64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gccgo-8-multilib-s390x-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gccgo-8-multilib-sparc64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gccgo-8-multilib-x86-64-linux-gnux32  # GNU Go compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gdc-7-aarch64-linux-gnu  # GNU D compiler (version 2) (cross compiler for arm64 architecture)
sudo apt install -y	gdc-7-alpha-linux-gnu  # GNU D compiler (version 2) (cross compiler for alpha architecture)
sudo apt install -y	gdc-7-arm-linux-gnueabi  # GNU D compiler (version 2) (cross compiler for armel architecture)
sudo apt install -y	gdc-7-arm-linux-gnueabihf  # GNU D compiler (version 2) (cross compiler for armhf architecture)
sudo apt install -y	gdc-7-hppa-linux-gnu  # GNU D compiler (version 2) (cross compiler for hppa architecture)
sudo apt install -y	gdc-7-i686-linux-gnu  # GNU D compiler (version 2) (cross compiler for i386 architecture)
sudo apt install -y	gdc-7-m68k-linux-gnu  # GNU D compiler (version 2) (cross compiler for m68k architecture)
sudo apt install -y	gdc-7-mips-linux-gnu  # GNU D compiler (version 2) (cross compiler for mips architecture)
sudo apt install -y	gdc-7-mips64-linux-gnuabi64  # GNU D compiler (version 2) (cross compiler for mips64 architecture)
sudo apt install -y	gdc-7-mips64el-linux-gnuabi64  # GNU D compiler (version 2) (cross compiler for mips64el architecture)
sudo apt install -y	gdc-7-mipsel-linux-gnu  # GNU D compiler (version 2) (cross compiler for mipsel architecture)
sudo apt install -y	gdc-7-multilib-arm-linux-gnueabihf  # GNU D compiler (version 2, multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gdc-7-multilib-i686-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gdc-7-multilib-mips-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for mips architecture)
sudo apt install -y	gdc-7-multilib-mips64-linux-gnuabi64  # GNU D compiler (version 2, multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gdc-7-multilib-mips64el-linux-gnuabi64  # GNU D compiler (version 2, multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gdc-7-multilib-mipsel-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gdc-7-multilib-powerpc-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gdc-7-multilib-powerpc64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gdc-7-multilib-s390x-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gdc-7-multilib-sparc64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gdc-7-multilib-x86-64-linux-gnux32  # GNU D compiler (version 2, multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gdc-7-powerpc-linux-gnu  # GNU D compiler (version 2) (cross compiler for powerpc architecture)
sudo apt install -y	gdc-7-powerpc-linux-gnuspe  # GNU D compiler (version 2) (cross compiler for powerpcspe architecture)
sudo apt install -y	gdc-7-powerpc64-linux-gnu  # GNU D compiler (version 2) (cross compiler for ppc64 architecture)
sudo apt install -y	gdc-7-powerpc64le-linux-gnu  # GNU D compiler (version 2) (cross compiler for ppc64el architecture)
sudo apt install -y	gdc-7-riscv64-linux-gnu  # GNU D compiler (version 2) (cross compiler for riscv64 architecture)
sudo apt install -y	gdc-7-s390x-linux-gnu  # GNU D compiler (version 2) (cross compiler for s390x architecture)
sudo apt install -y	gdc-7-sh4-linux-gnu  # GNU D compiler (version 2) (cross compiler for sh4 architecture)
sudo apt install -y	gdc-7-sparc64-linux-gnu  # GNU D compiler (version 2) (cross compiler for sparc64 architecture)
sudo apt install -y	gdc-7-x86-64-linux-gnux32  # GNU D compiler (version 2) (cross compiler for x32 architecture)
sudo apt install -y	gdc-8-aarch64-linux-gnu  # GNU D compiler (version 2) (cross compiler for arm64 architecture)
sudo apt install -y	gdc-8-alpha-linux-gnu  # GNU D compiler (version 2) (cross compiler for alpha architecture)
sudo apt install -y	gdc-8-arm-linux-gnueabi  # GNU D compiler (version 2) (cross compiler for armel architecture)
sudo apt install -y	gdc-8-arm-linux-gnueabihf  # GNU D compiler (version 2) (cross compiler for armhf architecture)
sudo apt install -y	gdc-8-hppa-linux-gnu  # GNU D compiler (version 2) (cross compiler for hppa architecture)
sudo apt install -y	gdc-8-i686-linux-gnu  # GNU D compiler (version 2) (cross compiler for i386 architecture)
sudo apt install -y	gdc-8-m68k-linux-gnu  # GNU D compiler (version 2) (cross compiler for m68k architecture)
sudo apt install -y	gdc-8-mips-linux-gnu  # GNU D compiler (version 2) (cross compiler for mips architecture)
sudo apt install -y	gdc-8-mips64-linux-gnuabi64  # GNU D compiler (version 2) (cross compiler for mips64 architecture)
sudo apt install -y	gdc-8-mips64el-linux-gnuabi64  # GNU D compiler (version 2) (cross compiler for mips64el architecture)
sudo apt install -y	gdc-8-mipsel-linux-gnu  # GNU D compiler (version 2) (cross compiler for mipsel architecture)
sudo apt install -y	gdc-8-multilib-arm-linux-gnueabihf  # GNU D compiler (version 2, multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gdc-8-multilib-i686-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gdc-8-multilib-mips-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for mips architecture)
sudo apt install -y	gdc-8-multilib-mips64-linux-gnuabi64  # GNU D compiler (version 2, multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gdc-8-multilib-mips64el-linux-gnuabi64  # GNU D compiler (version 2, multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gdc-8-multilib-mipsel-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gdc-8-multilib-powerpc-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gdc-8-multilib-powerpc64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gdc-8-multilib-s390x-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gdc-8-multilib-sparc64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gdc-8-multilib-x86-64-linux-gnux32  # GNU D compiler (version 2, multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gdc-8-powerpc-linux-gnu  # GNU D compiler (version 2) (cross compiler for powerpc architecture)
sudo apt install -y	gdc-8-powerpc-linux-gnuspe  # GNU D compiler (version 2) (cross compiler for powerpcspe architecture)
sudo apt install -y	gdc-8-powerpc64-linux-gnu  # GNU D compiler (version 2) (cross compiler for ppc64 architecture)
sudo apt install -y	gdc-8-powerpc64le-linux-gnu  # GNU D compiler (version 2) (cross compiler for ppc64el architecture)
sudo apt install -y	gdc-8-riscv64-linux-gnu  # GNU D compiler (version 2) (cross compiler for riscv64 architecture)
sudo apt install -y	gdc-8-s390x-linux-gnu  # GNU D compiler (version 2) (cross compiler for s390x architecture)
sudo apt install -y	gdc-8-sh4-linux-gnu  # GNU D compiler (version 2) (cross compiler for sh4 architecture)
sudo apt install -y	gdc-8-sparc64-linux-gnu  # GNU D compiler (version 2) (cross compiler for sparc64 architecture)
sudo apt install -y	gdc-8-x86-64-linux-gnux32  # GNU D compiler (version 2) (cross compiler for x32 architecture)
sudo apt install -y	gfortran-7-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gfortran-7-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gfortran-7-multilib-i686-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gfortran-7-multilib-mips-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gfortran-7-multilib-mips64-linux-gnuabi64  # GNU Fortran compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gfortran-7-multilib-mips64el-linux-gnuabi64  # GNU Fortran compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gfortran-7-multilib-mipsel-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gfortran-7-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gfortran-7-multilib-powerpc64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gfortran-7-multilib-s390x-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gfortran-7-multilib-sparc64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gfortran-7-multilib-x86-64-linux-gnux32  # GNU Fortran compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gfortran-8-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gfortran-8-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gfortran-8-multilib-i686-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gfortran-8-multilib-mips-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gfortran-8-multilib-mips64-linux-gnuabi64  # GNU Fortran compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gfortran-8-multilib-mips64el-linux-gnuabi64  # GNU Fortran compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gfortran-8-multilib-mipsel-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gfortran-8-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gfortran-8-multilib-powerpc64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gfortran-8-multilib-s390x-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gfortran-8-multilib-sparc64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gfortran-8-multilib-x86-64-linux-gnux32  # GNU Fortran compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gobjc-7-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gobjc-7-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gobjc-7-multilib-i686-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gobjc-7-multilib-mips-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gobjc-7-multilib-mips64-linux-gnuabi64  # GNU Objective-C compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gobjc-7-multilib-mips64el-linux-gnuabi64  # GNU Objective-C compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gobjc-7-multilib-mipsel-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gobjc-7-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gobjc-7-multilib-powerpc64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gobjc-7-multilib-s390x-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gobjc-7-multilib-sparc64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gobjc-7-multilib-x86-64-linux-gnux32  # GNU Objective-C compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	gobjc-8-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib support) (cross compiler for armel architecture)
sudo apt install -y	gobjc-8-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support) (cross compiler for armhf architecture)
sudo apt install -y	gobjc-8-multilib-i686-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for i386 architecture)
sudo apt install -y	gobjc-8-multilib-mips-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for mips architecture)
sudo apt install -y	gobjc-8-multilib-mips64-linux-gnuabi64  # GNU Objective-C compiler (multilib support) (cross compiler for mips64 architecture)
sudo apt install -y	gobjc-8-multilib-mips64el-linux-gnuabi64  # GNU Objective-C compiler (multilib support) (cross compiler for mips64el architecture)
sudo apt install -y	gobjc-8-multilib-mipsel-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for mipsel architecture)
sudo apt install -y	gobjc-8-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for powerpc architecture)
sudo apt install -y	gobjc-8-multilib-powerpc64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for ppc64 architecture)
sudo apt install -y	gobjc-8-multilib-s390x-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for s390x architecture)
sudo apt install -y	gobjc-8-multilib-sparc64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for sparc64 architecture)
sudo apt install -y	gobjc-8-multilib-x86-64-linux-gnux32  # GNU Objective-C compiler (multilib support) (cross compiler for x32 architecture)
sudo apt install -y	lib32gcc1-dbg-amd64-cross  # GCC support library (debug symbols) (amd64)
sudo apt install -y	lib32gcc1-dbg-mips64-cross  # GCC support library (debug symbols) (mips64)
sudo apt install -y	lib32gcc1-dbg-mips64el-cross  # GCC support library (debug symbols) (mips64el)
sudo apt install -y	lib32gcc1-dbg-ppc64-cross  # GCC support library (debug symbols) (ppc64)
sudo apt install -y	lib32gcc1-dbg-s390x-cross  # GCC support library (debug symbols) (s390x)
sudo apt install -y	lib32gcc1-dbg-sparc64-cross  # GCC support library (debug symbols) (sparc64)
sudo apt install -y	lib32gcc1-dbg-x32-cross  # GCC support library (debug symbols) (x32)
sudo apt install -y	lib64gcc1-dbg-i386-cross  # GCC support library (debug symbols) (i386)
sudo apt install -y	lib64gcc1-dbg-mips-cross  # GCC support library (debug symbols) (mips)
sudo apt install -y	lib64gcc1-dbg-mipsel-cross  # GCC support library (debug symbols) (mipsel)
sudo apt install -y	lib64gcc1-dbg-powerpc-cross  # GCC support library (debug symbols) (powerpc)
sudo apt install -y	lib64gcc1-dbg-x32-cross  # GCC support library (debug symbols) (x32)
sudo apt install -y	lib64gcc1-i386-cross  # GCC support library (i386) (64bit)
sudo apt install -y	lib64gcc1-mips-cross  # GCC support library (mips) (64bit)
sudo apt install -y	lib64gcc1-mipsel-cross  # GCC support library (mipsel) (64bit)
sudo apt install -y	lib64gcc1-powerpc-cross  # GCC support library (powerpc) (64bit)
sudo apt install -y	lib64gcc1-x32-cross  # GCC support library (x32) (64bit)
sudo apt install -y	libc++-10-dev  # LLVM C++ Standard library (development files)
sudo apt install -y	libc++-7-dev  # LLVM C++ Standard library (development files)
sudo apt install -y	libc++-8-dev  # LLVM C++ Standard library (development files)
sudo apt install -y	libc++-9-dev  # LLVM C++ Standard library (development files)
sudo apt install -y	libc++1-10  # LLVM C++ Standard library
sudo apt install -y	libc++1-7  # LLVM C++ Standard library
sudo apt install -y	libc++1-8  # LLVM C++ Standard library
sudo apt install -y	libc++1-9  # LLVM C++ Standard library
sudo apt install -y	libclang-10-dev  # Clang library  # Development package
sudo apt install -y	libclang-7-dev  # clang library  # Development package
sudo apt install -y	libclang-8-dev  # Clang library  # Development package
sudo apt install -y	libclang-9-dev  # Clang library  # Development package
sudo apt install -y	libclang-common-10-dev  # Clang library  # Common development package
sudo apt install -y	libclang-common-7-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-8-dev  # Clang library  # Common development package
sudo apt install -y	libclang-common-9-dev  # Clang library  # Common development package
sudo apt install -y	libclang-cpp10  # C++ interface to the Clang library
sudo apt install -y	libclang-cpp10-dev  # C++ interface to the Clang library
sudo apt install -y	libclang-cpp9  # C++ interface to the Clang library
sudo apt install -y	libclang1-10  # C interface to the Clang library
sudo apt install -y	libclang1-8  # C interface to the Clang library
sudo apt install -y	libclang1-9  # C interface to the Clang library
sudo apt install -y	libgcc1-alpha-cross  # GCC support library (alpha)
sudo apt install -y	libgcc1-amd64-cross  # GCC support library (amd64)
sudo apt install -y	libgcc1-armel-cross  # GCC support library (armel)
sudo apt install -y	libgcc1-dbg-alpha-cross  # GCC support library (debug symbols) (alpha)
sudo apt install -y	libgcc1-dbg-amd64-cross  # GCC support library (debug symbols) (amd64)
sudo apt install -y	libgcc1-dbg-arm64-cross  # GCC support library (debug symbols) (arm64)
sudo apt install -y	libgcc1-dbg-armel-cross  # GCC support library (debug symbols) (armel)
sudo apt install -y	libgcc1-dbg-armhf-cross  # GCC support library (debug symbols) (armhf)
sudo apt install -y	libgcc1-dbg-i386-cross  # GCC support library (debug symbols) (i386)
sudo apt install -y	libgcc1-dbg-mips-cross  # GCC support library (debug symbols) (mips)
sudo apt install -y	libgcc1-dbg-mips64-cross  # GCC support library (debug symbols) (mips64)
sudo apt install -y	libgcc1-dbg-mips64el-cross  # GCC support library (debug symbols) (mips64el)
sudo apt install -y	libgcc1-dbg-mipsel-cross  # GCC support library (debug symbols) (mipsel)
sudo apt install -y	libgcc1-dbg-powerpc-cross  # GCC support library (debug symbols) (powerpc)
sudo apt install -y	libgcc1-dbg-powerpcspe-cross  # GCC support library (debug symbols) (powerpcspe)
sudo apt install -y	libgcc1-dbg-ppc64-cross  # GCC support library (debug symbols) (ppc64)
sudo apt install -y	libgcc1-dbg-ppc64el-cross  # GCC support library (debug symbols) (ppc64el)
sudo apt install -y	libgcc1-dbg-riscv64-cross  # GCC support library (debug symbols) (riscv64)
sudo apt install -y	libgcc1-dbg-s390x-cross  # GCC support library (debug symbols) (s390x)
sudo apt install -y	libgcc1-dbg-sh4-cross  # GCC support library (debug symbols) (sh4)
sudo apt install -y	libgcc1-dbg-sparc64-cross  # GCC support library (debug symbols) (sparc64)
sudo apt install -y	libgcc1-dbg-x32-cross  # GCC support library (debug symbols) (x32)
sudo apt install -y	libgcc1-i386-cross  # GCC support library (i386)
sudo apt install -y	libgcc1-mips-cross  # GCC support library (mips)
sudo apt install -y	libgcc1-mips64-cross  # GCC support library (mips64)
sudo apt install -y	libgcc1-mips64el-cross  # GCC support library (mips64el)
sudo apt install -y	libgcc1-mipsel-cross  # GCC support library (mipsel)
sudo apt install -y	libgcc1-powerpcspe-cross  # GCC support library (powerpcspe)
sudo apt install -y	libgcc1-ppc64-cross  # GCC support library (ppc64)
sudo apt install -y	libgcc1-riscv64-cross  # GCC support library (riscv64)
sudo apt install -y	libgcc1-s390x-cross  # GCC support library (s390x)
sudo apt install -y	libgcc1-sh4-cross  # GCC support library (sh4)
sudo apt install -y	libgcc1-sparc64-cross  # GCC support library (sparc64)
sudo apt install -y	libgcc1-x32-cross  # GCC support library (x32)
sudo apt install -y	libgcc2-dbg-m68k-cross  # GCC support library (debug symbols) (m68k)
sudo apt install -y	libgcc2-m68k-cross  # GCC support library (m68k)
sudo apt install -y	libgcc4-dbg-hppa-cross  # GCC support library (debug symbols) (hppa)
sudo apt install -y	libgcc4-hppa-cross  # GCC support library (hppa)
sudo apt install -y	libhfgcc1-armel-cross  # GCC support library (armel) (hard float ABI)
sudo apt install -y	libhfgcc1-dbg-armel-cross  # GCC support library (debug symbols) (armel)
sudo apt install -y	libn32gcc1-dbg-mips-cross  # GCC support library (debug symbols) (mips)
sudo apt install -y	libn32gcc1-dbg-mips64-cross  # GCC support library (debug symbols) (mips64)
sudo apt install -y	libn32gcc1-dbg-mips64el-cross  # GCC support library (debug symbols) (mips64el)
sudo apt install -y	libn32gcc1-dbg-mipsel-cross  # GCC support library (debug symbols) (mipsel)
sudo apt install -y	libn32gcc1-mips-cross  # GCC support library (mips) (n32)
sudo apt install -y	libn32gcc1-mips64-cross  # GCC support library (mips64) (n32)
sudo apt install -y	libn32gcc1-mips64el-cross  # GCC support library (mips64el) (n32)
sudo apt install -y	libn32gcc1-mipsel-cross  # GCC support library (mipsel) (n32)
sudo apt install -y	libsfgcc1-armhf-cross  # GCC support library (armhf) (soft float ABI)
sudo apt install -y	libsfgcc1-dbg-armhf-cross  # GCC support library (debug symbols) (armhf)
sudo apt install -y	libx32gcc1-amd64-cross  # GCC support library (amd64) (x32)
sudo apt install -y	libx32gcc1-dbg-amd64-cross  # GCC support library (debug symbols) (amd64)
sudo apt install -y	libx32gcc1-dbg-i386-cross  # GCC support library (debug symbols) (i386)
sudo apt install -y	libx32gcc1-i386-cross  # GCC support library (i386) (x32)
sudo apt install -y	python-clang-7  # Clang Python Bindings
sudo apt install -y	python-clang-8  # Clang Python Bindings
sudo apt install -y	python-clang-9  # Clang Python Bindings
sudo apt install -y	python3-clang-10  # Clang Python Bindings
sudo apt install -y	gcc-7-multilib-x86-64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gcc-7-x86-64-linux-gnu  # GNU C compiler (cross compiler for amd64 architecture)
sudo apt install -y	gcc-8-multilib-x86-64-linux-gnu  # GNU C compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gcc-8-x86-64-linux-gnu  # GNU C compiler (cross compiler for amd64 architecture)
sudo apt install -y	gccgo-7-multilib-x86-64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gccgo-8-multilib-x86-64-linux-gnu  # GNU Go compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gdc-7-multilib-x86-64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gdc-7-x86-64-linux-gnu  # GNU D compiler (version 2) (cross compiler for amd64 architecture)
sudo apt install -y	gdc-8-multilib-x86-64-linux-gnu  # GNU D compiler (version 2, multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gdc-8-x86-64-linux-gnu  # GNU D compiler (version 2) (cross compiler for amd64 architecture)
sudo apt install -y	gfortran-7-multilib-x86-64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gfortran-8-multilib-x86-64-linux-gnu  # GNU Fortran compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gobjc-7-multilib-x86-64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	gobjc-8-multilib-x86-64-linux-gnu  # GNU Objective-C compiler (multilib support) (cross compiler for amd64 architecture)
sudo apt install -y	cpp-6  # GNU C preprocessor
sudo apt install -y	gcc-6  # GNU C compiler
sudo apt install -y	gcc-6-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-6-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-7-cross-base-ports  # GCC, the GNU Compiler Collection (library base package)
sudo apt install -y	golang-any  # Go programming language -- gccgo on "non-Go" platforms
sudo apt install -y	lib32gcc-6-dev  # GCC support library (32 bit development files)
sudo apt install -y	libgcc-6-dev  # GCC support library (development files)
sudo apt install -y	libgccjit-6-dev  # GCC just-in-time compilation (development files)
sudo apt install -y	libgccjit-6-doc  # GCC just-in-time compilation (documentation)
sudo apt install -y	libx32gcc-6-dev  # GCC support library (x32 development files)
sudo apt install -y	lib64gcc-6-dev  # GCC support library (64bit development files)
sudo apt install -y	gcj-5  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-jdk  # GCJ and Classpath development tools for Java(TM)
sudo apt install -y	gcj-5-jre-lib  # Java runtime library for use with gcj (jar files)
sudo apt install -y	libgcj16  # Java runtime library for use with gcj
sudo apt install -y	libgcj16-dev  # Java development headers for use with gcj
sudo apt install -y	uno-libs3-dbg  # LibreOffice UNO runtime environment -- public shared library debug symbols
sudo apt install -y	libclang1-3.6  # C interface to the clang library
sudo apt install -y	libgccjit-5-dbg  # GCC just-in-time compilation (debug information)
sudo apt install -y	llvm-3.6  # Modular compiler and toolchain technologies
sudo apt install -y	cableswig  # Generate wrappers for Python and Tcl from C++ code
sudo apt install -y	clang-3.5  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-3.5-doc  # C, C++ and Objective-C compiler (LLVM based)  # Documentation
sudo apt install -y	clang-3.6  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-3.6-doc  # C, C++ and Objective-C compiler (LLVM based)  # Documentation
sudo apt install -y	clang-3.7  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-3.7-doc  # C, C++ and Objective-C compiler (LLVM based)  # Documentation
sudo apt install -y	clang-3.8  # C, C++ and Objective-C compiler (LLVM based)
sudo apt install -y	clang-3.8-doc  # C, C++ and Objective-C compiler (LLVM based)  # Documentation
sudo apt install -y	colorgcc  # Colorizer for GCC warning/error messages
sudo apt install -y	cpp-4.7  # GNU C preprocessor
sudo apt install -y	cpp-4.7-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-4.7-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-4.8-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.8-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-4.8-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.8-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.9-aarch64-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.9-arm-linux-gnueabi  # GNU C preprocessor
sudo apt install -y	cpp-4.9-arm-linux-gnueabihf  # GNU C preprocessor
sudo apt install -y	cpp-4.9-powerpc-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.9-powerpc64le-linux-gnu  # GNU C preprocessor
sudo apt install -y	cpp-4.9-s390x-linux-gnu  # GNU C preprocessor
sudo apt install -y	gcc-4.7-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.7-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.7-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.7-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-4.7-multilib  # GNU C compiler (multilib files)
sudo apt install -y	gcc-4.7-multilib-arm-linux-gnueabi  # GNU C compiler (multilib files)
sudo apt install -y	gcc-4.7-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib files)
sudo apt install -y	gcc-4.7-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-4.7-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcc-4.8-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.8-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.8-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.8-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-aarch64-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-arm-linux-gnueabi-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-arm-linux-gnueabihf-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-locales  # GCC, the GNU compiler collection (native language support files)
sudo apt install -y	gcc-4.9-powerpc-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-powerpc64le-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-s390x-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gccgo-4.7  # GNU Go compiler
sudo apt install -y	gccgo-4.7-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-4.7-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-4.7-multilib  # GNU Go compiler (multilib files)
sudo apt install -y	gccgo-4.8-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.8-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-4.8-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.8-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.9  # GNU Go compiler
sudo apt install -y	gccgo-4.9-aarch64-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.9-arm-linux-gnueabi  # GNU Go compiler
sudo apt install -y	gccgo-4.9-arm-linux-gnueabihf  # GNU Go compiler
sudo apt install -y	gccgo-4.9-powerpc-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.9-powerpc64le-linux-gnu  # GNU Go compiler
sudo apt install -y	gccgo-4.9-s390x-linux-gnu  # GNU Go compiler
sudo apt install -y	gdc-4.8-aarch64-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.8-arm-linux-gnueabihf  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.8-powerpc-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.8-powerpc64le-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-aarch64-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-arm-linux-gnueabi  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-arm-linux-gnueabihf  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-powerpc-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-powerpc64le-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gdc-4.9-s390x-linux-gnu  # GNU D compiler (version 2), based on the GCC backend
sudo apt install -y	gfortran-4.7  # GNU Fortran compiler
sudo apt install -y	gfortran-4.7-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-4.7-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-4.7-multilib  # GNU Fortran compiler (multilib files)
sudo apt install -y	gfortran-4.7-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib files)
sudo apt install -y	gfortran-4.7-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib files)
sudo apt install -y	gfortran-4.8-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.8-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-4.8-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.8-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-aarch64-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-arm-linux-gnueabi  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-arm-linux-gnueabihf  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-powerpc-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-powerpc64le-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-s390x-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gnat-4.9  # GNU Ada compiler
sudo apt install -y	gnat-4.9-base  # GNU Ada compiler (common files)
sudo apt install -y	gnat-4.9-doc  # GNU Ada compiler (documentation)
sudo apt install -y	gnat-4.9-sjlj  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gnat-mingw-w64-base  # GNU Ada compiler for MinGW-w64 (base package)
sudo apt install -y	gobjc++-4.7  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.7-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.7-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.7-multilib  # GNU Objective-C++ compiler (multilib files)
sudo apt install -y	gobjc++-4.7-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib files)
sudo apt install -y	gobjc++-4.7-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib files)
sudo apt install -y	gobjc++-4.8-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.8-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.8-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.8-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-aarch64-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-arm-linux-gnueabi  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-arm-linux-gnueabihf  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-powerpc-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-powerpc64le-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc++-4.9-s390x-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc-4.7  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.7-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.7-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.7-multilib  # GNU Objective-C compiler (multilib files)
sudo apt install -y	gobjc-4.7-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib files)
sudo apt install -y	gobjc-4.7-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib files)
sudo apt install -y	gobjc-4.8-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.8-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.8-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.8-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-aarch64-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-arm-linux-gnueabi  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-arm-linux-gnueabihf  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-powerpc-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-powerpc64le-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	gobjc-4.9-s390x-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	libclang1-3.5-dbg  # clang library
sudo apt install -y	libclang1-3.6-dbg  # clang library
sudo apt install -y	libclang1-3.7-dbg  # clang library
sudo apt install -y	libclang1-3.8-dbg  # clang library
sudo apt install -y	libeigen2-dev  # lightweight C++ template library for linear algebra
sudo apt install -y	libgnat-4.9  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnat-4.9-dbg  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnatprj4.9  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatprj4.9-dbg  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj4.9-dev  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatvsn4.9  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libgnatvsn4.9-dbg  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn4.9-dev  # GNU Ada compiler selected components (development files)
sudo apt install -y	python-ctypeslib  # code generator to convert header files into ctypes interfaces
sudo apt install -y	python-py++  # OO-framework for creating a code generator for Boost.Python
sudo apt install -y	python-pyzolib  # Utilities for the Pyzo environment (Python 2)
sudo apt install -y	python3-pyzolib  # Utilities for the Pyzo environment (Python 3)
sudo apt install -y	autoconf2.59  # automatic configure script builder (obsolete version)
sudo apt install -y	clang-3.5-examples  # Clang examples
sudo apt install -y	clang-3.6-examples  # Clang examples
sudo apt install -y	clang-3.7-examples  # Clang examples
sudo apt install -y	clang-3.8-examples  # Clang examples
sudo apt install -y	cpp-5-hppa-linux-gnu  # GNU C preprocessor
sudo apt install -y	gcc-4.7  # GNU C compiler
sudo apt install -y	gcc-4.7-arm-linux-gnueabi  # GNU C compiler
sudo apt install -y	gcc-4.7-arm-linux-gnueabihf  # GNU C compiler
sudo apt install -y	gcc-4.7-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-4.8-aarch64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.8-arm-linux-gnueabihf  # GNU C compiler
sudo apt install -y	gcc-4.8-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.8-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.8-powerpc-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.8-powerpc64le-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.9-aarch64-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.9-arm-linux-gnueabi  # GNU C compiler
sudo apt install -y	gcc-4.9-arm-linux-gnueabihf  # GNU C compiler
sudo apt install -y	gcc-4.9-doc  # Documentation for the GNU compilers (gcc, gobjc, g++)
sudo apt install -y	gcc-4.9-multilib-arm-linux-gnueabi  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.9-multilib-arm-linux-gnueabihf  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.9-multilib-powerpc-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.9-multilib-s390x-linux-gnu  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.9-powerpc-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.9-powerpc64le-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-4.9-s390x-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-hppa-linux-gnu  # GNU C compiler
sudo apt install -y	gcc-5-hppa-linux-gnu-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-arm-linux-androideabi  # cross toolchain and binutils for Android/Bionic on ARM
sudo apt install -y	gcc-i686-linux-android  # cross toolchain and binutils for Android/Bionic on ARM
sudo apt install -y	gccgo-4.7-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-4.8-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-4.9-doc  # Documentation for the GNU Go compiler (gccgo)
sudo apt install -y	gccgo-4.9-multilib  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-4.9-multilib-powerpc-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccgo-4.9-multilib-s390x-linux-gnu  # GNU Go compiler (multilib support)
sudo apt install -y	gccxml  # XML output extension to GCC
sudo apt install -y	gcj-4.8  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.8-aarch64-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.8-arm-linux-gnueabihf  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.8-jdk  # GCJ and Classpath development tools for Java(TM)
sudo apt install -y	gcj-4.8-jre-lib  # Java runtime library for use with gcj (jar files)
sudo apt install -y	gcj-4.8-powerpc-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.8-powerpc64le-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-aarch64-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-arm-linux-gnueabi  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-arm-linux-gnueabihf  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-powerpc-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-powerpc64le-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-s390x-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-aarch64-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-alpha-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-arm-linux-gnueabi  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-arm-linux-gnueabihf  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-hppa-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-m68k-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-mips-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-mips64-linux-gnuabi64  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-mips64el-linux-gnuabi64  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-mipsel-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-powerpc-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-powerpc-linux-gnuspe  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-powerpc64-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-powerpc64le-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-s390x-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-sh4-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-5-sparc64-linux-gnu  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-aarch64-linux-gnu  # GNU Java compiler (based on GCC) for the arm64 architecture
sudo apt install -y	gcj-alpha-linux-gnu  # GNU Java compiler (based on GCC) for the alpha architecture
sudo apt install -y	gcj-arm-linux-gnueabi  # GNU Java compiler (based on GCC) for the armel architecture
sudo apt install -y	gcj-arm-linux-gnueabihf  # GNU Java compiler (based on GCC) for the armhf architecture
sudo apt install -y	gcj-hppa-linux-gnu  # GNU Java compiler (based on GCC) for the hppa architecture
sudo apt install -y	gcj-m68k-linux-gnu  # GNU Java compiler (based on GCC) for the m68k architecture
sudo apt install -y	gcj-mips-linux-gnu  # GNU Java compiler (based on GCC) for the mips architecture
sudo apt install -y	gcj-mips64-linux-gnuabi64  # GNU Java compiler (based on GCC) for the mips64 architecture
sudo apt install -y	gcj-mips64el-linux-gnuabi64  # GNU Java compiler (based on GCC) for the mips64el architecture
sudo apt install -y	gcj-mipsel-linux-gnu  # GNU Java compiler (based on GCC) for the mipsel architecture
sudo apt install -y	gcj-powerpc-linux-gnu  # GNU Java compiler (based on GCC) for the powerpc architecture
sudo apt install -y	gcj-powerpc-linux-gnuspe  # GNU Java compiler (based on GCC) for the powerpcspe architecture
sudo apt install -y	gcj-powerpc64-linux-gnu  # GNU Java compiler (based on GCC) for the ppc64 architecture
sudo apt install -y	gcj-powerpc64le-linux-gnu  # GNU Java compiler (based on GCC) for the ppc64el architecture
sudo apt install -y	gcj-s390x-linux-gnu  # GNU Java compiler (based on GCC) for the s390x architecture
sudo apt install -y	gcj-sh4-linux-gnu  # GNU Java compiler (based on GCC) for the sh4 architecture
sudo apt install -y	gcj-sparc64-linux-gnu  # GNU Java compiler (based on GCC) for the sparc64 architecture
sudo apt install -y	gdc-5-hppa-linux-gnu  # GNU D compiler (version 2)
sudo apt install -y	gfortran-4.8-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-4.8-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-4.9-multilib-arm-linux-gnueabi  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-4.9-multilib-arm-linux-gnueabihf  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-4.9-multilib-powerpc-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-4.9-multilib-s390x-linux-gnu  # GNU Fortran compiler (multilib support)
sudo apt install -y	gfortran-5-hppa-linux-gnu  # GNU Fortran compiler
sudo apt install -y	gnat-5-hppa-linux-gnu  # GNU Ada compiler
sudo apt install -y	gnat-5-sjlj-hppa-linux-gnu  # GNU Ada compiler (setjump/longjump runtime library)
sudo apt install -y	gobjc++-4.8-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.8-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.9-multilib  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.9-multilib-arm-linux-gnueabi  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.9-multilib-arm-linux-gnueabihf  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.9-multilib-powerpc-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-4.9-multilib-s390x-linux-gnu  # GNU Objective-C++ compiler (multilib support)
sudo apt install -y	gobjc++-5-hppa-linux-gnu  # GNU Objective-C++ compiler
sudo apt install -y	gobjc-4.8-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.8-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.9-multilib  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.9-multilib-arm-linux-gnueabi  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.9-multilib-arm-linux-gnueabihf  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.9-multilib-powerpc-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-4.9-multilib-s390x-linux-gnu  # GNU Objective-C compiler (multilib support)
sudo apt install -y	gobjc-5-hppa-linux-gnu  # GNU Objective-C compiler
sudo apt install -y	lib32gcc-4.7-dev  # GCC support library (32 bit development files)
sudo apt install -y	lib32gcc-4.9-dev-s390x-cross  # GCC support library (32 bit development files)
sudo apt install -y	lib64gcc-4.8-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	lib64gcc-4.9-dev-powerpc-cross  # GCC support library (64bit development files)
sudo apt install -y	libclang-3.5-dev  # clang library  # Development package
sudo apt install -y	libclang-3.6-dev  # clang library  # Development package
sudo apt install -y	libclang-3.7-dev  # clang library  # Development package
sudo apt install -y	libclang-3.8-dev  # clang library  # Development package
sudo apt install -y	libclang-common-3.5-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-3.6-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-3.7-dev  # clang library  # Common development package
sudo apt install -y	libclang-common-3.8-dev  # clang library  # Common development package
sudo apt install -y	libclang1-3.5  # C interface to the clang library
sudo apt install -y	libclang1-3.7  # C interface to the clang library
sudo apt install -y	libclang1-3.8  # C interface to the clang library
sudo apt install -y	libgcc-4.7-dev  # GCC support library (development files)
sudo apt install -y	libgcc-4.7-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.7-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.8-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.8-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.8-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.8-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-arm64-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-armel-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-armhf-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-powerpc-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-ppc64el-cross  # GCC support library (development files)
sudo apt install -y	libgcc-4.9-dev-s390x-cross  # GCC support library (development files)
sudo apt install -y	libgcc-5-dev-hppa-cross  # GCC support library (development files)
sudo apt install -y	libgccxml-dev  # Libraries for building extension to gccxml output
sudo apt install -y	libgcj14  # Java runtime library for use with gcj
sudo apt install -y	libgcj14-dev  # Java development headers for use with gcj
sudo apt install -y	libgmpv4-dev  # Multiprecision arithmetic library developers tools (GCC 4.x compatible)
sudo apt install -y	libgmpxxv4-4  # Multiprecision arithmetic library (C++ bindings, GCC 4.x compatible)
sudo apt install -y	libgnat-5-dbg-hppa-cross  # runtime for applications compiled with GNAT (debugging symbols)
sudo apt install -y	libgnat-5-hppa-cross  # runtime for applications compiled with GNAT (shared library)
sudo apt install -y	libgnatprj5-dbg-hppa-cross  # GNU Ada compiler Project Manager (debugging symbols)
sudo apt install -y	libgnatprj5-dev-hppa-cross  # GNU Ada compiler Project Manager (development files)
sudo apt install -y	libgnatprj5-hppa-cross  # GNU Ada compiler Project Manager (shared library)
sudo apt install -y	libgnatvsn5-dbg-hppa-cross  # GNU Ada compiler selected components (debugging symbols)
sudo apt install -y	libgnatvsn5-dev-hppa-cross  # GNU Ada compiler selected components (development files)
sudo apt install -y	libgnatvsn5-hppa-cross  # GNU Ada compiler selected components (shared library)
sudo apt install -y	libhfgcc-4.7-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhfgcc-4.9-dev-armel-cross  # GCC support library (hard float ABI development files)
sudo apt install -y	libhts1  # C library for high-throughput sequencing data formats
sudo apt install -y	libsfgcc-4.7-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgcc-4.8-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libsfgcc-4.9-dev-armhf-cross  # GCC support library (soft float ABI development files)
sudo apt install -y	libx32gcc-4.7-dev  # GCC support library (x32 development files)
sudo apt install -y	llvm-3.5  # Modular compiler and toolchain technologies
sudo apt install -y	python-clang-3.5  # Clang Python Bindings
sudo apt install -y	python-clang-3.6  # Clang Python Bindings
sudo apt install -y	python-clang-3.7  # Clang Python Bindings
sudo apt install -y	python-clang-3.8  # Clang Python Bindings
sudo apt install -y	lib64gcc-4.7-dev  # GCC support library (64bit development files)
sudo apt install -y	gcc-5-plugin-dev-hppa-linux-gnu  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-mozilla  # GCC, the GNU Compiler Collection
sudo apt install -y	cpp-4.9  # GNU C preprocessor
sudo apt install -y	gcc-4.9  # GNU C compiler
sudo apt install -y	gcc-4.9-base  # GCC, the GNU Compiler Collection (base package)
sudo apt install -y	gcc-4.9-multilib  # GNU C compiler (multilib support)
sudo apt install -y	gcc-4.9-plugin-dev  # Files for GNU GCC plugin development.
sudo apt install -y	gcc-4.9-source  # Source of the GNU Compiler Collection
sudo apt install -y	gcj-4.9  # GCJ byte code and native compiler for Java(TM)
sudo apt install -y	gcj-4.9-jdk  # GCJ and Classpath development tools for Java(TM)
sudo apt install -y	gcj-4.9-jre-lib  # Java runtime library for use with gcj (jar files)
sudo apt install -y	gcj-jdk  # gcj and Classpath development tools for Java(TM)
sudo apt install -y	gfortran-4.9  # GNU Fortran compiler
sudo apt install -y	gfortran-4.9-multilib  # GNU Fortran compiler (multilib support)
sudo apt install -y	hardening-wrapper  # Compiler wrapper to enable security hardening flags
sudo apt install -y	lib32gcc-4.9-dev  # GCC support library (32 bit development files)
sudo apt install -y	libgcc-4.9-dev  # GCC support library (development files)
sudo apt install -y	libgcj15  # Java runtime library for use with gcj
sudo apt install -y	libgcj15-dev  # Java development headers for use with gcj
sudo apt install -y	libx32gcc-4.9-dev  # GCC support library (x32 development files)
sudo apt install -y	lib64gcc-4.9-dev  # GCC support library (64bit development files)

