# newdebian
	copy grub
	change to root
	sudo apt update
	apt install sudo
	sudo apt install vim
	sudo apt install net-tools
	sudo apt install tmux, byobu
	sudo apt install tree
	change user as sudoer
		sudo visudo ===>> username ALL=(ALL:ALL) ALL
		sudo usermod -aG sudo debian
	
	mkdir ~/.ssh
	touch authorized_keys
	or ssh-keygen -t RSA	
	alias ===>> ll, poweroff, reboot, shutdown -p
	
	fdisk
	lvm
	swap
