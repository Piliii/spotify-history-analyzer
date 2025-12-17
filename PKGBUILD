# Maintainer: pili <contact@ayopili.com>

pkgname=spotify-history-analyzer
pkgver=1.0.0
pkgrel=1
pkgdesc="Analyze Spotify history and generate statistics"
arch=('any')
license=('MIT')
depends=('python')

source=("spotify-history-analyzer" "LICENSE")
sha256sums=('SKIP' 'SKIP')

package() {
    install -Dm755 spotify-history-analyzer \
        "$pkgdir/usr/bin/spotify-history-analyzer"

    install -Dm644 LICENSE \
        "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
