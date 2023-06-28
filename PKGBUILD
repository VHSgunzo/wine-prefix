# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='wine-prefix'
pkgver='0.0.3'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Default wine prefix for Lutris Wine'
url="https://github.com/VHSgunzo/wine-prefix"
arch=('x86_64')
license=('MIT')
source=('defprefix.xz.lwpfx')
sha256sums=('SKIP')

package() {
  install -Dm644 "$source" "${pkgdir}/opt/lwrap/prefix_backups/$source"
}
