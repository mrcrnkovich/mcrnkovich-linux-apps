pkgbase=mcrnkovich
pkgname=(mcrnkovich-base mcrnkovich-apps mcrnkovich-sway mcrnkovich-utils mcrnkovich-xwayland)
pkgver=1.4.2
pkgrel=1
pkgdesc="mcrnkovich applications packages"
arch=("x86_64")

package_mcrnkovich-apps() {
    depends=( 'aerc' 
        'chromium' 'firefox' 'lynx'
        'libreoffice-fresh' 'gimp'
        'zathura' 'zathura-pdf-mupdf'
    )
    optdepends=( 'reaper-bin' 'zoom' )
}

package_mcrnkovich-base() {
    depends=( 
        'acpi' 'autoconf' 'automake' 'base' 'bc'
        'binutils' 'bison' 'fakeroot'
        'gcc' 'ghc' 'go'
        'file' 'findutils' 'flex' 'fwupd' 'gawk' 'gettext'
        'git' 'grep' 'groff' 'htop' 'libtool'
        'linux' 'linux-firmware'
        'pacman' 'pacman-contrib'
        'm4' 'make' 
        'paprefs' 'patch'
        'perf' 'pkgconf' 'stack' 'strace' 'sudo' 'texinfo'
        'gzip' 'unzip'
        'terminus-font'
        'rsync' 'which' 'zsh'
    )

    depends+=( 'docker' 'docker-compose' )
    depends+=( 'pyenv' 'python' 'python-pip' 'python-pipenv')

    # Networking
    depends+=( 'curl' 'nmap' 'iwd' 'openssh' 'wget' )
    depends+=( 'alacritty' 'vim' 'tmux' 'fzf' 'fd' 'jq' 'neovim' 'ripgrep')
}

package_mcrnkovich-sway() {
    depends=('sway' 'swayidle' 'swaylock' 'i3status' )
    depends+=(
        'gnome-keyring' 'gnome-themes-extra'
        'lxappearance' 'qt5-wayland'
    )
   
    # app launcher 
    depends+=( 'fuzzel' )   
 
    # Fonts
    depends+=( 'ttf-fira-code' 'ttf-font-awesome' 'ttf-opensans' 'ttf-roboto')

    depends+=( 'xf86-video-intel' 'xf86-video-vesa')
    depends+=( 'dunst' 'light' 'imv')
    optdepends+=( 'wlsunset' 'wev' )
}

package_mcrnkovich-utils(){
    pkgdesc="Utils for Sound, Printing, Bluetooth"
    arch=("x86_64")
    depends=(
        'alsa-firmware' 'alsa-utils'
        'pavucontrol' 'pulseaudio-bluetooth'
        'sof-firmware' 'sof-tools'
    )
     depends+=(
         'pipewire' 'pipewire-alsa' 'pipewire-jack' 'pipewire-pulse'
         'wireplumber' 'xdg-desktop-portal-wlr'
     )
    depends+=( 'cups' 'cups-pdf' )
    depends+=( 'bluez' 'bluez-utils' )
}

package_mcrnkovich-xwayland(){
    pkgdesc="X11 meta package"
    arch=("x86_64")
    depends=(
        'xorg-bdftopcf' 'xorg-docs' 'xorg-font-util' 'xorg-fonts-100dpi' 'xorg-fonts-75dpi'
        'xorg-iceauth' 'xorg-mkfontscale' 'xorg-server' 'xorg-server-devel' 'xorg-server-xephyr'
        'xorg-server-xnest' 'xorg-server-xvfb' 'xorg-sessreg' 'xorg-smproxy' 'xorg-x11perf'
        'xorg-xauth' 'xorg-xbacklight' 'xorg-xcmsdb' 'xorg-xcursorgen' 'xorg-xdpyinfo'
        'xorg-xdriinfo' 'xorg-xev' 'xorg-xgamma' 'xorg-xhost' 'xorg-xinit' 'xorg-xinput'
        'xorg-xkbevd' 'xorg-xkbutils' 'xorg-xkill' 'xorg-xlsatoms' 'xorg-xlsclients' 'xorg-xmodmap'
        'xorg-xpr' 'xorg-xprop' 'xorg-xrandr' 'xorg-xrdb' 'xorg-xrefresh' 'xorg-xset' 'xorg-xsetroot'
        'xorg-xvinfo' 'xorg-xwayland' 'xorg-xwd' 'xorg-xwininfo' 'xorg-xwud'
    )
}
