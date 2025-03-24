# new debian
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
	scp -P4000 .bash_aliases debian@192.168.1.105:/home/debian
	

	vim /etc/network/interfaces
	# The loopback network interface auto lo
	iface lo inet loopback
	 
	# The primary network interface
	auto ens36
	iface ens36  inet static
	 address 192.168.2.236
	 netmask 255.255.255.0
	 gateway 192.168.2.254
	 dns-nameservers 192.168.2.254
	 
	 sudo systemctl restart networking.service


	fdisk
	lvm
	swap
	aliases
