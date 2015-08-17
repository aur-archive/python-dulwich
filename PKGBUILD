# Maintainer: Christoph Kappel <chkappel@gmail.com>
# Contributor: Alessandro Nakamuta <alessandro dot ufms at gmail dot com>
# Contributor: Lukas Linhart <bugs@almad.net>

pkgname=python-dulwich
pkgver=0.9.0
pkgrel=1
pkgdesc="Dulwich is a pure-Python implementation of the Git file formats and protocols."
arch=("i686" "x86_64")
url="http://samba.org/~jelmer/dulwich/"
license=("GPL2")
depends=("python2")
makedepends=("python2-distribute")
source=("http://samba.org/~jelmer/dulwich/dulwich-$pkgver.tar.gz")
md5sums=("472d37679f77d627d8e1721ea80b6729")

build() {
  cd "$srcdir/dulwich-$pkgver"

  python2 setup.py install --root="$pkgdir/" --optimize=1
}

