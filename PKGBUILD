# Contributor: Neale Pickett <neale@woozle.org>

pkgname=runit-desktop
pkgver=1.2
pkgrel=1
pkgdesc="Startup scripts for a runit-based desktop"
arch=(any)
url="http://woozle.org/neale/g.cgi/aur/runit-desktop"
license=(BSD)
depends=(runit-init busybox)
optdepends=(
	'xorg-xdm: X Display manager'
)
source=('git+http://woozle.org/neale/g.cgi/aur/runit-desktop')
md5sums=(SKIP)

package () {
	echo $srcdir/$pkgname
	cd $srcdir/$pkgname
	make PREFIX=$pkgdir
}
