# Contributor: Nebulosa <nebulosa2007 na yandekse>

pkgname=2gis-ufa
pkgver=36
pkgrel=1
pkgdesc="Map of Ufa for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Ufa-${pkgver}.orig.zip")
md5sums=('5555291e18bb9bff76e9ed5809bacc3b')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Ufa.dgdat "${startdir}/pkg/opt/2gis/ufa.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Ufa.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Ufa.dglf" || return 1

}
