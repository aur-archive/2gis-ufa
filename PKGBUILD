# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-ufa
pkgver=41
pkgrel=1
pkgdesc="Map of Ufa for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Ufa-${pkgver}.orig.zip")
md5sums=('25c7d7b7680cf4a5517f26f2c6f6aa22')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Ufa.dgdat "${startdir}/pkg/opt/2gis/ufa.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Ufa.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Ufa.dglf" || return 1
     
}

