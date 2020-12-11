# Maintainer: archcrack <johndoe.arch@outlook.com>

pkgname=sids
pkgver=0.3.2
pkgrel=1
pkgdesc=""
arch=(any)
url="https://github.com/leo-arch/xaide"
license=(GPL2+)
depends=('coreutils' 'gawk' 'findutils')
makedepends=('git')
source=("git+${url}.git")
#sha256sums=('SKIP')
sha256sums=('SKIP')

package() {
  cd "${srcdir}/${pkgname}"
  install -Dm755 $pkgname "${pkgdir}/usr/bin/$pkgname"
}
