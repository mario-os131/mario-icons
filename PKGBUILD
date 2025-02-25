pkgname=mario-icons
pkgver=1.0
pkgrel=1
pkgdesc="Super Mario-themed icons for Mario Linux"
arch=('any')
license=('GPL')
source=("https://github.com/mario-os131/mario-icons/archive/refs/tags/v1.0.tar.gz")
sha256sums=('SKIP')

package() {
    cd "$srcdir/$pkgname-$pkgver"
    install -Dm644 icons/* "$pkgdir/usr/share/icons/mario-icons/"
}


