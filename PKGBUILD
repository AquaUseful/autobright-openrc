# Maintainer: AquaUseful
pkgname=autobright-openrc
pkgver=1
pkgrel=1
pkgdesc=""
arch=('any')
url=""
license=('MIT')
groups=()
depends=('autobright')
source=(
    'autobright.initd' 
    'autobright.confd'
)
sha256sums=(
    '72d6b817abb99a65510f2b4d4a9f7ed7b217ea1e8a09d106b22360af911237c4'
    '7b30b02af05fd61511c6139230325a3c0ae1fc898f29ce7fc66510e99bcf8b41'
    )

package() {
    install -m 755 -D "$srcdir"/autobright.initd "$pkgdir"/etc/init.d/autobright
    install -m 755 -D "$srcdir"/autobright.confd "$pkgdir"/etc/conf.d/autobright
}
