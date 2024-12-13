# Maintainer: Your Name <your.email@example.com>
pkgname=prime-finder
pkgver=1.0.0
pkgrel=1
pkgdesc="A cool prime number finder that shows primes in a given range"
arch=('any')
url="https://github.com/ArmanTahsinAdib/prime-finder"
license=('MIT')
depends=('python>=3.8')
source=("$pkgname")
sha256sums=('SKIP')

package() {
    install -Dm755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
