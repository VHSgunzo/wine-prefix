# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgbase='wine-prefix'
pkgname=('wine-prefix' 'wine-prefix-dotnet')
pkgver='0.0.3'
pkgrel='1'
url="https://github.com/VHSgunzo/wine-prefix"
arch=('x86_64')
license=('MIT')
source=(
    "$url/releases/download/v$pkgver/defprefix.xz.lwpfx"
    "$url/releases/download/v$pkgver/defprefix_dotnet.xz.lwpfx"
)
sha256sums=('SKIP' 'SKIP')

package_wine-prefix() {
    pkgdesc='Default wine prefix for Lutris Wine'
    srclwpfx="defprefix.xz.lwpfx"
    install -Dm644 "$srclwpfx" "${pkgdir}/opt/lwrap/prefix_backups/$srclwpfx"
}

package_wine-prefix-dotnet() {
    pkgdesc='Default wine prefix with dotnet for Lutris Wine'
    srclwpfx="defprefix_dotnet.xz.lwpfx"
    install -Dm644 "$srclwpfx" "${pkgdir}/opt/lwrap/prefix_backups/$srclwpfx"
}
