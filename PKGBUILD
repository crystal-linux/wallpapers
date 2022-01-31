# Maintainer: Matt C <mdc028[at]bucknell[dot]edu>

pkgname=crystal-wallpapers
pkgver=1.0.1
pkgrel=1
pkgdesc="Crystal Linux Wallpaper Images"
arch=('any')
url="https://git.tar.black/crystal/wallpapers"
license=('GPL')
source=()
depends=()
conflicts=()
md5sums=()

package() {

    mkdir -p "${pkgdir}/usr/share/backgrounds/crystal"
    cp -rv ../*.jpg  ../*.png ../*.svg "${pkgdir}/usr/share/backgrounds/crystal/."
    
}
