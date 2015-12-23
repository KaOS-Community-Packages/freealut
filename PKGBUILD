pkgname=freealut
pkgver=1.1.0
pkgrel=5
pkgdesc="OpenAL Utility Toolkit (ALUT)"
arch=('x86_64')
url="http://www.openal.org"
license=("LGPL")
depends=('openal')
source=("${pkgname}-${pkgver}.tar.gz::http://mirror.hactar.bz/extra/os/x86_64/${pkgname}-${pkgver}-${pkgrel}-x86_64.pkg.tar.xz")
md5sums=('e5e08244f7adf0c9ba36ad0d3c8b860a')

package() {
  cd "${srcdir}"
  install -d "${pkgdir}"/usr
        cp -r usr "${pkgdir}"/
}

