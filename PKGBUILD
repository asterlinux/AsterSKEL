#Maintainer: Sahan Rasanjana <sahan.user@gmail.com>
pkgname=("aster-qtile-skel")
_destname="/etc"
pkgver=1
pkgrel=7
pkgdesc="aster linux skel packge"
arch=("x86_64")
url="https://github.com/asterlinux/AsterSKEL"
license=('GPL')
depends=("qtile" "nitrogen" "hyfetch" "picom" "alacritty")
makedepends=("git")
source=("skel.tar.gz")
sha256sums=("SKIP")
package() {
        install -dm755 ${pkgdir}${_destname}/skel
        cp -r ${srcdir}/skel ${pkgdir}${_destname}
}
