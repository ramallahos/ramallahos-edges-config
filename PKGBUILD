# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-edges-config
pkgver=1
pkgrel=1
pkgdesc="Variety config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('edges')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/edges/"
    install -Dm 644 "edges.conf" "${pkgdir}/etc/skel/.config/edges/edges.conf"
}
