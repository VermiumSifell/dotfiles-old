pacman -S stow polybar i3-gaps alacritty rofi ttf-font-awesome slock zsh playerctl brightnessctl

sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

git clone https://github.com/VermiumSifell/dotfiles

cd dotfiles

stow *
