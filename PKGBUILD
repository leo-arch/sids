# Maintainer: archcrack <johndoe.arch@outlook.com>

pkgname=sids
pkgver=0.4.5
pkgrel=1
pkgdesc="A Simple Instrusion Detection System written in Bash"
arch=(any)
url="https://github.com/leo-arch/sids"
license=(GPL3)
depends=('gawk' 'findutils')
makedepends=('git')
source=("git+${url}.git")
sha256sums=('SKIP')

package() {
  cd "${srcdir}/${pkgname}"
  install -Dm755 $pkgname "${pkgdir}/usr/bin/$pkgname"
}
