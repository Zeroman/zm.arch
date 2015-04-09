# Maintainer: Zeroman Yang <51feel@gmail.com>

pkgname=zm
pkgver=0.0.1
pkgrel=1
pkgdesc="Make archlinux to a single sfs file on aufs"
arch=('any')
url="http://www.51feel.info/"
license=('GPL')
depends=('grub' 'squashfs-tools' 'rsync' 'mkinitcpio' 'cdrtools' 'lzo' 'xz' 'gzip')
optdepends=('xz: Use lzma or xz compression for the initramfs image'
            'pixz: Parallel, indexed xz compressor'
            'axel: Download accelerator'
            'bzip2: Use bzip2 compression for the initramfs image'
            'lzop: Use lzo compression for the initramfs image')
# provides=('mkinitcpio')
# conflicts=('mkinitcpio')
# backup=('etc/mkinitcpio.conf')
source=('git://github.com/Zeroman/zm.git')

package() {
    cd zm
    ./zm --install-pkg "${pkgdir}"
}

sha256sums=('SKIP')
