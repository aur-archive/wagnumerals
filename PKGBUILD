# Contributor: mystax <mystax@wagn.me>
# Maintainer: mystax <mystax@wagn.me>
pkgname=wagnumerals
pkgver=2.0.1
pkgrel=2
pkgdesc="Command that parodies Roman numerals."
url="http://pastebin.com/dhKxuZmi"
license=("Torin License")
depends=()
arch=('any') 
makedepends=('gcc')
source=('wagnumerals.c')
md5sums=('e9c12dce0ef7c3f6aaffe999d512629d')

build() {
  cd "$srcdir"
  gcc -std=c99 -o wagnumerals wagnumerals.c
  mkdir -p $pkgdir/usr/bin
  cp wagnumerals $pkgdir/usr/bin
  chmod +x $pkgdir/usr/bin/wagnumerals
}
