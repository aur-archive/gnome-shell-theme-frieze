# Maintainer:  Joost Bremmer <toost.b[at]gmail[dot]com>
# Contributor: Harv Chen <ch05042210[at]gmail[dot]com>
# Contributor: Lucas Saliés Brum <luca[at]archlinux[dot]com[dot]br>
pkgname=gnome-shell-theme-frieze
pkgver=3.6.0.1
pkgrel=3
pkgdesc="Gnome Shell + GDM Theme"
url="http://nuxio.deviantart.com/art/Frieze-Gnome-Shell-270456342"
arch=('x86_64' 'i686')
license=('GPLv3')
depends=('gnome-shell=3.6'
'ttf-roboto')
optdepends=('gnome-tweak-tool'
'gdm')
source=("http://frieze-gnome-shell.googlecode.com/files/frieze_3.6-0.1.tar.gz")
sha256sums=('2831904320eeb1104d15c07b67631433e5b9d54ecde92e4d7da093197f46e17d')

package() {
    tar zxf "${srcdir}/frieze_3.6-0.1.tar.gz"
    mkdir -p "${pkgdir}/usr/share/themes"
    cp -R "${srcdir}/Frieze" "${pkgdir}/usr/share/themes"
}
