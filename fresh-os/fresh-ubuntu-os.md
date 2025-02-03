# new ubuntu
	copy grub
	sudo apt update
	sudo apt install vim (if minimal os)
	sudo apt install iputils-ping
	sudo apt install net-tools ===>> ifconfig
	sudo apt install tmux, byobu
	sudo apt install tree
	hostnamectl set-hostname srv2
	vim /etc/hosts
	vim /etc/hostname
	change /etc/apt/sources.list to us and ir
	change password root
	copy publickey to server
	change ip /etc/netplan/*.yamel
		network:
		  version: 2
		  renderer: networkd
		  ethernets:
		    ens3:
		      dhcp4: no
		      addresses:
			- 192.168.121.221/24
		      gateway4: 192.168.121.1
		      nameservers:
			  addresses: [8.8.8.8, 1.1.1.1]
			  
		netplan try or netplan apply
		
		sudo vim /etc/ssh/sshd_config
			config file	
	unlink /etc/resolv.conf
	vim /etc/resolv.conf
		nameservers 8.8.8.8
		nameservers 4.2.2.4
	set interface
	set ip
	touch /home/behnam/.ssh/config
		include /home/behnam/.ssh/conhfig.d/*.conf
	config /home/behnam/.ssh/config.d
		HostName srv1
			Host 192.1681.1.110
			Port 22
			User behnam
			
			
			
	fdisk
	lvm
	swap
	aliases
	
	
	
	
	
