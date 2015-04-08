# Maintainer: Zeroman Yang <51feel@gmail.com>

pkgname=zm
pkgver=.r5.g715a37b
pkgrel=0.0.1
pkgdesc="Make archlinux to a single sfs file on aufs"
arch=('any')
url="http://www.51feel.info/"
license=('GPL')
depends=('grub2' 'squashfs-tools')
optdepends=('xz: Use lzma or xz compression for the initramfs image'
            'bzip2: Use bzip2 compression for the initramfs image'
            'lzop: Use lzo compression for the initramfs image'
            'mkinitcpio-nfs-utils: Support for root filesystem on NFS')
# provides=('mkinitcpio')
# conflicts=('mkinitcpio')
# backup=('etc/mkinitcpio.conf')
# source=('git://projects.archlinux.org/mkinitcpio.git')

package() {
    ./zm --install-pkg "${pkgdir}"
}

sha256sums=('SKIP')
