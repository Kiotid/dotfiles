# dotfiles
sudo pacman -S thunar lolcat cowsay fortune neofetch cmatrix neovim polybar rofi cava kitty nitrogen fish nodejs npm python python-pip exa imagemagick git
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
rm -rf ../paru
paru -S picom clipit cava
