# dotfiles
sudo pacman -S thunar lolcat cowsay fortune neofetch cmatrix neovim rofi cava kitty nitrogen fish nodejs npm python3 python-pip exa imagemagick git notify-osd figlet

git clone https://aur.archlinux.org/paru.git

cd paru

makepkg -si

rm -rf ../paru

paru -S picom clipit cava eww-git pipes.sh
