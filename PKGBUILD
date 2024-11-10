pkgname="axskel-awesome"
pkgver="4.3"
pkgrel="1"
pkgdesc="Calla desktop environement and AxAwEd configurations"
arch=("x86_64")
depends=("xorg-server" "pipewire-pulse"
         "brightnessctl" "inotify-tools"
         "awesome-git" "picom" "maim"
         "papirus-icon-theme" "noto-fonts"
         "noto-fonts-cjk" "noto-color-emoji-fontconfig"
         "noto-fonts-extra")
url="https://github.com/LeVraiArdox/calla"
optdepends=("st: terminal",
            "vim-gtk3: vim with clipboard",
            "nemo: file manager",
            "network-manager-gnome: network applet",
            "polkit-gnome: polkit",
            "cbatticon: battery applet",
            "blueman: bluetooth applet",
            "xdg-user-dirs: generate home directories")

package(){
   mkdir -p "${pkgdir}/etc/"
   cp -r "${srcdir}/skel" "${pkgdir}/etc/"
}
