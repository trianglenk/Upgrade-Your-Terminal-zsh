Upgrade-Your-Terminal-zsh

<div align="center">
  <img src="zsh-ter.png" alt="Логотип проекта" width="95%">
</div>



A script for quickly setting up a beautiful and convenient terminal based on zsh + Oh My Zsh with useful plugins and the Powerlevel10k theme.

💿 Installation

Debian/Ubuntu

sudo apt install -y zsh git curl

Arch Linux

sudo pacman -Syu --needed zsh git curl

Fedora

sudo dnf install -y zsh git curl

Run the script

sh -c "$(curl -fsSL https://raw.githubusercontent.com/<username>/Upgrade-Your-Terminal-zsh/main/install.sh)"

The script automatically:





installs Oh My Zsh;



sets zsh as the default shell;



installs the Powerlevel10k theme and the zsh-autosuggestions and zsh-syntax-highlighting plugins;



wires everything up in ~/.zshrc.

🚀 What you get





🎨 The Powerlevel10k theme with an informative prompt (git status, time, exit code);



⌨️ Command autosuggestions as you type;



🌈 Syntax highlighting: valid commands in green, invalid ones in red;



🧩 Essential Oh My Zsh plugins: git, z, extract, sudo and more.

⚙️ Manual setup





Change the default shell:

 chsh -s $(which zsh)



Install Oh My Zsh:

 sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"



Add to ~/.zshrc:

 ZSH_THEME="powerlevel10k/powerlevel10k"
 plugins=(git z extract sudo zsh-autosuggestions zsh-syntax-highlighting)

📝 Requirements





Linux (Debian/Ubuntu, Arch, Fedora) or WSL2;



git and curl;



the MesloLGS NF font (the script will notify you if it's missing).

