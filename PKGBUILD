# Maintainer: Alexander Rødseth <rodseth@gmail.com>

pkgname=bumpver
pkgver=0.42
pkgrel=1
pkgdesc='Utilities for bumping the pkgver or pkgrel in a PKGBUILD'
arch=('any')
url='https://github.com/xyproto/bumpver'
license=('GPL2')
depends=('bash' 'setconf' 'getver')
makedepends=('git')
source=("git://github.com/xyproto/bumpver#tag=$pkgver")
md5sums=('SKIP')

package() {
  install -d "$pkgdir/usr/bin"
  install -m755 "$pkgname/bumpver.sh" "$pkgdir/usr/bin/bumpver"
  install -m755 "$pkgname/bumprel.sh" "$pkgdir/usr/bin/bumprel"
  install -m755 "$pkgname/bup.sh" "$pkgdir/usr/bin/bup"
  install -m755 "$pkgname/geturlver.sh" "$pkgdir/usr/bin/geturlver"
}

# vim:set ts=2 sw=2 et:
