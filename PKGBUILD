pkgbase=presage2-lang
pkgname=("${pkgbase}-de-de"
                        "${pkgbase}-en-us"
                        "${pkgbase}-es-es"
                        "${pkgbase}-et-ee"
                        "${pkgbase}-fi-fi"
                        "${pkgbase}-hu-hu"
                        "${pkgbase}-ru-ru"
                        "${pkgbase}-sv-se")
pkgver=22.01.01
pkgrel=1
pkgdesc="Presage language support for"
arch=('any')
depends=("presage2")
url="https://github.com/sailfish-keyboard/presage-database"

license=('Apache-2.0 License')
source=("${url}/archive/$pkgver/prestrage-database-$pkgver.tar.gz")
sha256sums=('815b1e2e00a0b9e58f5954f1489710f2f76dd82a0efa7cb8638f40404ee5b57e')

package_presage2-lang-de-de() {
    pkgdesc="${_desc} German"
    provides=("${pkgbase}-de_DE")
    conflicts=("${pkgbase}-de_DE")
    replaces=("${pkgbase}-de_DE")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_de_DE $pkgdir/usr/share/presage/
}

package_presage2-lang-en-us() {
    pkgdesc="${_desc} English US"
    provides=("${pkgbase}-en_US")
    conflicts=("${pkgbase}-en_US")
    replaces=("${pkgbase}-en_US")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_en_US $pkgdir/usr/share/presage/
}

package_presage2-lang-es-es() {
    pkgdesc="${_desc} Spanish (or Castilian)"
    provides=("${pkgbase}-es_ES")
    conflicts=("${pkgbase}-es_ES")
    replaces=("${pkgbase}-es_ES")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_es_ES $pkgdir/usr/share/presage/
}

package_presage2-lang-et-ee() {
    pkgdesc="${_desc} Estonian"
    provides=("${pkgbase}-et_EE")
    conflicts=("${pkgbase}-et_EE")
    replaces=("${pkgbase}-et_EE")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_et_EE $pkgdir/usr/share/presage/
}

package_presage2-lang-fi-fi() {
    pkgdesc="${_desc} Finnish"
    provides=("${pkgbase}-fi_FI")
    conflicts=("${pkgbase}-fi_FI")
    replaces=("${pkgbase}-fi_FI")

    mkdir -p $pkgdir/usr/share/presage
    cp -R presage-database-${pkgver}/databases/database_fi_FI $pkgdir/usr/share/presage/
}

package_presage2-lang-hu-hu() {
    pkgdesc="${_desc} Hungarian"
    provides=("${pkgbase}-hu_HU")
    conflicts=("${pkgbase}-hu_HU")
    replaces=("${pkgbase}-hu_HU")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_hu_HU $pkgdir/usr/share/presage/
}

package_presage2-lang-ru-ru() {
    pkgdesc="${_desc} Russian"
    provides=("${pkgbase}-ru_RU")
    conflicts=("${pkgbase}-ru_RU")
    replaces=("${pkgbase}-ru_RU")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_ru_RU $pkgdir/usr/share/presage/
}

package_presage2-lang-sv-se() {
    pkgdesc="${_desc} Swedish"
    provides=("${pkgbase}-sv_SE")
    conflicts=("${pkgbase}-sv_SE")
    replaces=("${pkgbase}-sv_SE")

    mkdir -p $pkgdir/usr/share/presage/
    cp -R presage-database-${pkgver}/databases/database_sv_SE $pkgdir/usr/share/presage/
}
