pkgname=theming
pkgver=1
pkgrel=1
pkgdesc="destop settings for vampire "
arch=('any')
license=('GPL3')
depends=('bash')
makedepends=('git')
groups=('vampire')
source=("$pkgname::git+https://github.com/Vampire-Offical/theming.git")
md5sums=('SKIP')



package() {

    mkdir -p $pkgdir/usr/share/backgrounds/vampire
    mkdir -p $pkgdir/usr/share/icons/vampire/
    mkdir -p $pkgdir/etc
    cd $srcdir/$pkgname
    cp -r backgrounds $pkgdir/usr/share/
    cp -r gnome-background-properties $pkgdir/usr/share/
    cp -r gnome-shell $pkgdir/usr/share/
    cp -r themes $pkgdir/usr/share/
    cp -r skel $pkgdir/etc/
    cp logo.png $pkgdir/usr/share/icons/vampire/

}
