# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgbase='wine-prefix'
pkgname=('wine-prefix' 'wine-prefix-dotnet')
pkgver='0.0.7'
pkgrel='1'
url="https://github.com/VHSgunzo/wine-prefix"
arch=('x86_64')
license=('MIT')
srclwpfx="defprefix.xz.lwpfx"
srcdotnetlwpfx="defprefix_dotnet.xz.lwpfx"
source=(
    "$url/releases/download/v$pkgver/$srclwpfx"
    "$url/releases/download/v$pkgver/$srcdotnetlwpfx"
)
sha256sums=('SKIP' 'SKIP')

package_wine-prefix() {
    pkgdesc='Default wine prefix for Lux Wine'
    install -Dm644 "$srclwpfx" "${pkgdir}/opt/lwrap/prefix_backups/$srclwpfx"
}

package_wine-prefix-dotnet() {
    pkgdesc='Default wine prefix with dotnet for Lux Wine'
    install -Dm644 "$srcdotnetlwpfx" "${pkgdir}/opt/lwrap/prefix_backups/$srcdotnetlwpfx"
}
