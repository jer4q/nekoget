pkgname=nekoget
pkgver=0.4.0
pkgrel=1
pkgdesc="A simple cli tool for fetching random catgirl images from NekosAPI & yande.re"
arch=('x86_64')
url="https://github.com/jer4q/nekoget"
license=('MIT')
depends=('python' 'python-pillow' 'python-pyperclip' 'python-requests' 'wget')
source=(https://github.com/jer4q/nekoget.git)
sha256sums=('SKIP')

build() {
  cd "$srcdir"
  git clone https://github.com/jer4q/nekoget.git
  cd nekoget
}

package() {
  cd "$srcdir/nekoget"
  install -Dm755 nekoget "$pkgdir/usr/bin/nekoget"
  install -Dm755 iv-cli "$pkgdir/usr/share/nekoget/iv-cli"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

