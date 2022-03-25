# arch-quick-start


sudo pacman -Syyu a52dec faac faad2 flac jasper lame libdca libdv libmad libmpeg2 libtheora libvorbis libxv wavpack x264 xvidcore p7zip tar rsync xorg bluez blueman bluez-utils dialog ifplugd wpa_supplicant pavucontrol alsa-firmware alsa-utils alsa-plugins pulseaudio-alsa pulseaudio base-devel git automake gcc vlc xf86-input-synaptics gedit ffmpeg unzip neofetch

sudo snap install brave

sudo ln -s /var/lib/snapd/snap /snap

sudo snap install code --classic

yay -Syu discord

sudo nano /etc/pacman.conf

[alerque]
Server = https://arch.alerque.com/$arch

[core-x86-64-v3]
Include = /etc/pacman.d/alhp-mirrorlist

[extra-x86-64-v3]
Include = /etc/pacman.d/alhp-mirrorlist

[community-x86-64-v3]
Include = /etc/pacman.d/alhp-mirrorlist

[andontie-aur]
Server = https://aur.andontie.net/$arch

[arcanisrepo]
Server = http://repo.arcanis.me/$arch

[arch4edu]
Server = https://mirrors.tuna.tsinghua.edu.cn/arch4edu/$arch
## or other mirrors in https://github.com/arch4edu/arch4edu/wiki/Add-arch4edu-to-your-Archlinux

[archlinuxcn]
Server = http://repo.archlinuxcn.org/$arch
## or install archlinuxcn-mirrorlist-git and use the mirrorlist
#Include = /etc/pacman.d/archlinuxcn-mirrorlist

[archstrike]
Server = https://mirror.archstrike.org/$arch/$repo

[archzfs]
# Origin Server - France
Server = http://archzfs.com/$repo/x86_64
# Mirror - Germany
Server = http://mirror.sum7.eu/archlinux/archzfs/$repo/x86_64
# Mirror - Germany
Server = https://mirror.biocrafting.net/archlinux/archzfs/$repo/x86_64
# Mirror - India
Server = https://mirror.in.themindsmaze.com/archzfs/$repo/x86_64
# Mirror - US
Server = https://zxcvfdsa.com/archzfs/$repo/$arch

[artafinde]
Server = https://pkgbuild.com/~artafinde/repo

[ashleyis]
Server = http://arch.ashleytowns.id.au/repo/$arch

[avr]
Server = https://bouchaud.org/packages/$repo/$arch

[aviallon]
Server = https://mirror.lesviallon.fr/$repo/os/$arch

[berberman]
Server = https://repo.typed.icu/$arch

[BioArchLinux]
Server = https://repo.bioarchlinux.org/$arch

[blackeagle-pre-community]
Server = https://repo.herecura.be/$repo/$arch

[coderkun-aur]
Server = https://arch.suruatoel.xyz/$repo/$arch/

[dasbaumwolltier]
Server = https://repo.guldner.eu/repository/archlinux/$arch/

[desolve]
Server = https://desolve.ru/archrepo/$arch

[dkp-libs]
Server = https://downloads.devkitpro.org/packages
[dkp-linux]
Server = https://downloads.devkitpro.org/packages/linux

[ear]
Server = https://ear.wardsegers.be/$arch

[ffy00]
Server = https://pkgbuild.com/~ffy00/repo

[home_fusion809_Arch_Extra]
Server = https://download.opensuse.org/repositories/home:/fusion809/Arch_Extra/$arch

[grawlinson]
Server = https://mirror.little.kiwi
Server = https://pkgbuild.com/~grawlinson/repo/$repo

[herecura]
Server = https://repo.herecura.be/$repo/$arch

[holo]
Server = https://repo.holocm.org/archlinux/x86_64

[home-thaodan]
Server = https://thaodan.de/public/archlinux/home-thaodan/$arch

[ivasilev]
Server = https://ivasilev.net/pacman/$arch

[home_justkidding_arch_Arch]
Server = https://download.opensuse.org/repositories/home:/justkidding:/arch/Arch/$arch

[jlk]
Server = https://jlk.fjfi.cvut.cz/arch/repo

[kernel-lts]
Server = https://repo.m2x.dev/current/$repo/$arch

[linux-nitrous]
Server = https://github.com/xdevs23/linux-nitrous/releases/latest/download

[liquorix]
Server = https://liquorix.net/archlinux/$repo/$arch

[markzz]
Server = https://repo.markzz.com/arch/$repo/$arch

[maximbaz]
Server = https://pkgbuild.com/~maximbaz/repo/

[miffe]
Server = https://arch.miffe.org/$arch/

[mikelpint]
Server = https://mikelpint.github.io/repository/archlinux/repo

[home_Minerva_W_Science_Arch_Extra]
Server = https://download.opensuse.org/repositories/home:/Minerva_W:/Science/Arch_Extra/$arch 

[mobile]
Server = https://keybase.pub/farwayer/arch/$repo/

[mxmeinhold]
Server = https://arch.mxmeinhold.com/$arch

[orhun]
Server = https://pkgbuild.com/~orhun/repo

[origincode]
Server = https://repo.origincode.me/repo/$arch

[oscloud]
Server = http://repo.oscloud.info/

[ownstuff-testing]
Server = https://ftp.f3l.de/~martchus/$repo/os/$arch
Server = https://martchus.no-ip.biz/repo/arch/$repo/os/$arch

[ownstuff]
Server = https://ftp.f3l.de/~martchus/$repo/os/$arch
Server = https://martchus.no-ip.biz/repo/arch/$repo/os/$arch

[phillid-custom]
Server = https://repo.nah.nz/$repo

[pkgbuilder]
Server = https://pkgbuilder-repo.chriswarrick.com/

[home_post-factum_kernels_Arch]
Server = https://download.opensuse.org/repositories/home:/post-factum:/kernels/Arch/$arch

[home_pbek_QOwnNotes_Arch_Extra]
Server = https://download.opensuse.org/repositories/home:/pbek:/QOwnNotes/Arch_Extra/$arch

[qt-debug]
Server = https://qutebrowser.org/qt-debug/$arch

[quarry]
Server = https://pkgbuild.com/~anatolik/quarry/x86_64/

[realtime]
Server = https://pkgbuild.com/~dvzrv/repos/realtime/$arch

[seblu]
Server = https://al1.seblu.net/$repo/$arch
Server = https://al2.seblu.net/$repo/$arch

[seiichiro]
Server = https://www.seiichiro0185.org/repo/$arch

[sergej-repo]
Server = http://repo.p5n.pp.ru/$repo/os/$arch

[slowbro]
Server = http://www.slowbro.org/arch/$arch/

[sublime-text]
Server = https://download.sublimetext.com/arch/stable/x86_64

[subtitlecomposer]
Server = https://smoothware.net/$repo/$arch

[supermario]
Server = https://pkgs.finelli.dev/arch/$arch

[therepoclub]
Server = https://arch.therepo.club/$arch/

[trinity]
Server = https://mirror.ppa.trinitydesktop.org/trinity/archlinux

[valveaur]
Server = http://repo.steampowered.com/arch/valveaur

[xfce4-devel]
Server = https://repo.m2x.dev/current/$repo/$arch

[xuanrui]
Server = https://arch.xuanruiqi.com/repo

[xyne-x86_64]
Server = https://xyne.dev/repos/xyne

[alucryd]
Server = https://pkgbuild.com/~alucryd/$repo/x86_64

[alucryd-multilib]
Server = https://pkgbuild.com/~alucryd/$repo/x86_64

[andrwe]
Server = http://repo.andrwe.org/$arch

[archgeotux]
Server = https://sourceforge.net/projects/$repo/files/$arch/

[archlinuxfr]
Server = http://repo.archlinux.fr/$arch

[archlinuxgr]
Server = http://archlinuxgr.tiven.org/archlinux/$arch


[archlinuxir]
Server = https://mirror.bardia.tech/archlinuxir/$arch

[archlinuxgr-kde4]
Server = http://archlinuxgr.tiven.org/archlinux-kde4/$arch

[archlinux-phalcon]
Server = https://archlinux-phalcon.gitlab.io/repository

[archlinux-php]
Server = https://archlinux-php.gitlab.io/repository

[archmint]
Server = https://sourceforge.net/projects/archmint/files/repo/$arch

[dx37essentials]
Server = https://dx37.gitlab.io/$repo/$arch

[extra-alucryd]
Server = https://pkgbuild.com/~alucryd/$repo/$arch

[python]
Server = https://ffy00.github.io/arch-python-repo/

[heftig]
Server = https://pkgbuild.com/~heftig/repo/$arch

[juju]
Server = https://repo.juju2143.ca/archlinux/$repo/os/$arch

[kernel]
Server = https://www.blacksky3.com/$arch/$repo

[mesa-git]
Server = https://pkgbuild.com/~lcarlier/$repo/$arch

[oracle]
Server = http://linux.shikadi.net/arch/$repo/$arch/

[pietma]
Server = http://repository.pietma.com/nexus/content/repositories/archlinux/$arch/$repo

[pnsft-pur]
Server = https://osdn.net/projects/ponsfoot-aur/storage/pur/x86_64/

[rstudio]
Server = https://aur1.gitlab.io/$repo/$arch

[stx4-any]
Server = https://starterx4.keybase.pub/repos/arch/any/stx4

[stx4-x86_64]
Server = https://starterx4.keybase.pub/repos/arch/x86_64/stx4

[symbiflow-git]
Server = https://ffy00.github.io/symbiflow-arch-pkgs/

[thirtythreeforty]
Server = https://archrepo.thirtythreeforty.net/repo/thirtythreeforty

[userrepository]
Server = https://userrepository.eu

[vdr4arch]
Server = https://vdr4arch.github.io/$arch
