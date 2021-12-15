# Maintainer: somekool <somekool _ at _ gmail _ dot _com>

#srcgiturl=https://github.com/mathieujobin/imlib1-aur
pkgname=imlib1
pkgver=v1.8.2
pkgrel=1
pkgdesc="imlib 1.8.2 (for Enlightenment legacy versions)"
arch=('i686' 'x86_64')
url="http://enlightenment.org"
license=('GPLv2')
depends=('gcc8')
optdepends=()
# makedepends=('git' 'scons' 'cmake') 'libssl-dev')
source=("imlib-1.8.2.tar.gz"::"http://www.somekool.net/HTML/smk2k3/stuff/imlib-1.8.2.tar.gz")
md5sums=('11c482bd9cd360ec6c7110629f1759f4')

build() {
  cd ${srcdir}/imlib-1.8.2
  gcc-8 -o e *.c -lX11 -lXext
  echo ======================== build completed ========================
}

package() {
  #mkdir -p ${pkgdir}/usr/local/enlightenment/bin/
  #mv ${srcdir}/enl-0.13.3/e ${pkgdir}/usr/local/enlightenment/bin/e-13.3

  echo ======================== package completed ========================
}

