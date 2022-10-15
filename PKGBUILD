# Maintainer: voj343 <voj343@yandex.com>
pkgname=mullvad-openrc
pkgver=1.0
pkgrel=2
pkgdesc="mullvad openrc service"
arch=('any')
url='https://github.com/voj343/mullvad-openrc'
license=('GPL')
depends=('openrc')
source=("mullvadd.initd")
sha256sums=("3c0d6016088c969d8f89339069e5b83503f5e434b0b811ff1d7e2197063a3f73")

package() {
  install -Dm755 ${srcdir}/mullvadd.initd "$pkgdir"/etc/init.d/mullvadd
  install=mullvadd.install
}
