# Maintainer: twa022 <twa022 at gmail dot com>

pkgname=mintdm-themes-linuxmint
_name=mint-mdm-themes
pkgver=1.1.2
pkgrel=2
pkgdesc="Themes for MDM from LinuxMint"
arch=('any')
url="http://www.linuxmint.com"
license=('GPL')
depends=('mdm-display-manager')
source=("http://packages.linuxmint.com/pool/main/m/${_name}/${_name}_${pkgver}.tar.gz")

package() {
	cd ${srcdir}/${_name}-${pkgver}
	cp -R usr "${pkgdir}"
	cp -R unused-themes/* "${pkgdir}/usr/share/mdm/html-themes"
}

sha256sums=('35647f82a8afd2f3e4d8929726c6080ea671134e01f42add70b8a9e1ebe364aa')
