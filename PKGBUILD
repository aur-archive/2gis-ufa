pkgname=2gis-ufa
pkgver=71
pkgrel=1
pkgdesc="Map of Ufa for 2GIS, February 2014"
arch=('i686' 'x86_64')
url="http://ufa.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Ufa-71.orig.zip")
md5sums=('1d2ac7eea5789ef0906493a37e352ee8')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Ufa.dgdat" "${pkgdir}/opt/2gis/ufa.dgdat" || return 1
  
}
