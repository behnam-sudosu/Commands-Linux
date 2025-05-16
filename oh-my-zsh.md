# oh my zsh
	sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
	sh -c "$(wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
	sudo apt update
	sudo apt install oh my zsh
	vim ~/.zshrc
		ZSH_THEME="fino-time"