# Not finished yet

# Maintainer: Antoni Spaanderman <56turtle56@gmail.com>

pkgname=simple-usb-automount
pkgver=1.0.1
pkgrel=1
arch=('any')
url=https://github.com/antonilol/simple-usb-automount
license=('MIT')
source=("simple-usb-automount::git+$url#tag=v$pkgver")
md5sums=('SKIP')

package() {
  cd "$pkgname"
  mkdir -p "$pkgdir"/{usr/local/bin,etc/{systemd/system,udev/rules.d}}
  ./install rw "$pkgdir"
}


