pkgname=kysnow
pkgver=1.0
pkgrel=7
pkgdesc="Plays Low Tier God in your terminal, Made by Tonsuke"
arch=('any')
license=('unknown')
depends=('mpv' 'python' 'python-opencv' 'python-numpy')
source=('kysnow' 'KYSNOW' 'video.mp4')
sha256sums=('SKIP' 'SKIP' 'SKIP')

package() {
  install -Dm755 kysnow "$pkgdir/usr/bin/kysnow"
  install -Dm755 KYSNOW "$pkgdir/usr/bin/KYSNOW"
  install -Dm644 video.mp4 "$pkgdir/usr/share/kysnow/video.mp4"
}
