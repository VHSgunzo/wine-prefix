# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='wine-prefix'
pkgver='0.0.3'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Default wine prefix for Lutris Wine'
url="https://github.com/VHSgunzo/wine-prefix"
arch=('x86_64')
license=('MIT')
srclwpfx="defprefix.xz.lwpfx"
source=("$url/releases/download/v$pkgver/$srclwpfx")
sha256sums=('SKIP')

package() {
  install -Dm644 "$srclwpfx" "${pkgdir}/opt/lwrap/prefix_backups/$srclwpfx"
}
