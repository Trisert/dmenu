pkgname=dmenu-trisert-git
_pkgname=dmenu
pkgver=0.8.2.r1062.2087ab9
pkgdesc="dmenu"
pkgrel=1
url='https://github.com/Trisert/dmenu'
arch=('i686' 'x86_64')
license=('MIT')
options=('zipman')
depends=('libxft')
makedepends=('ncurses' 'libxext' 'git')
optdepends=('dmenu: feed urls to dmenu')
source=('git://github.com/Trisert/dmenu')
md5sums=('SKIP')

provides=("${_pkgname}")
conflicts=("${_pkgname}")

package() {
        cd "${_pkgname}"
        make PREFIX=/usr DESTDIR="${pkgdir}" install
}

