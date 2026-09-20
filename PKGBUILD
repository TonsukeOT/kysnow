pkgname=kysnow
pkgver=1.0
pkgrel=1
pkgdesc="Plays Low tier god in your terminal, made by Tonsuke"
arch=('any')
license=('unknown')
depends=('mpv')
source=('kysnow' 'video.mp4')
sha256sums=('SKIP' 'SKIP')

package() {
  install -Dm755 kysnow "$pkgdir/usr/bin/kysnow"
  install -Dm644 video.mp4 "$pkgdir/usr/share/kysnow/video.mp4"
}
