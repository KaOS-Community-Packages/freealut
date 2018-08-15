pkgname=freealut
pkgver=1.1.0
pkgrel=2
pkgdesc="OpenAL Utility Toolkit (ALUT)"
arch=('x86_64')
url="http://www.openal.org"
license=("LGPL")
depends=('openal')
source=("http://pkgs.fedoraproject.org/repo/pkgs/freealut/freealut-1.1.0.tar.gz/e089b28a0267faabdb6c079ee173664a/freealut-1.1.0.tar.gz")
md5sums=('e089b28a0267faabdb6c079ee173664a')

build() {
  cd $srcdir/$pkgname-$pkgver
  ./configure --prefix=/usr  --disable-static
  make
}

package() {
  cd $srcdir/$pkgname-$pkgver
  make DESTDIR=$pkgdir install
}

