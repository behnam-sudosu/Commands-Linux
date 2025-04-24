# notes from Milad Norouzi
	unser ===>> unser variable
	export (variable)
	echo $? ===>> see error or wright
	echo $$ ===>> new shell id
	uname -a
	lsb_release -a
	cat /etc/os-release
	car > file1
	echo " " > .bash-history
	tail -n 14
	tail -f
	sed "s/yes/no/g" file1
	sed -i "s/yes/no/g" file1 ===>> -i insert
	find . -type f ===>> file
	find . -type d ===>> directory
	find . -name behnam
	find . -iname behnam
	find . -user
	find . -group
	find . -perm
	find . -delete
	find . -size +100M -size -200M
	locate ===>> apt install mlocate or plocate
	updatedb
	zip file1.zip file1
	unzip file1.zip
	gzip file1
	gunzip file1.gz
	bzip2 file1
	bunzip2 file1.bz2
	xz file1
	unxz file1.xz
	file file1 ===>> material file1
	tar -cvf my.tar file1
	tar -xvf my.tar file1
	tar -czvf my.tar.gz file1 ===>> make gzip
	tar -cjvf my.tar.bz2 file1 ===>> make bz2
	dd if=/sda of /dev/sdb
	jobs
	ps -aux
	ps -fl ===>> show nice
	pgrep sleep
	ps -aux | grep sleep
	bpytop
	fdisk
	gdisk
	lsblk
	mkfs -t ext4 /dev/sdb1
	blkid
	mkfs.ext /dev/sdb1
	mount /dev/sdb1 /tmp
	vim /etc/fstab
	mount -a
	ls -l /dev/disk/by-uuid
	umont /tmp
	du -sh *
	df -hi
	fsck.ext4 /dev/sdb1
	fsck.ext4 -f /dev/sdb1 ===>> -f force
	tune2fs -l /dev/sdb1
	dump2fs /dev/sdb1
	chmod u+x file1
	chmod g+x file1
	chmod o+x file1
	chown behnam:behnam file1
	nonloginshell
		/etc/profile
		/etc/bash.bashrc
		/etc/profile.d ===>> put script someone login send and email for you
	loginshell
		change pass
		.profile
		.bashrc
	alias mn="rm -rf /"
	.bashrc ===>> alias
	.bash-aliases ===>> /home
	source .bashrc
	/etc/skel
	myfun(){
	ls
	}
	add to .bashrc
	mylist={
	lsts learn linux}
	echo ${mylist[1]}
	#!/bin/bash ===>> make file sh
	bash file ===>> no need x
	bash -x file1 ===>> debug
	chost
	xhost - ===>> enable
	xhost +192.168.1.100 ===>> can ssh to your desktop linux
	passwd ===>> change curent user password
	useradd -m ===>> create home directory
	useradd -d /apt/behnam ===>> change home directory
	useradd -c "user"===>> comment
	useradd -s /bin/bash ===>> choose shell
	usermod
	userdel
	usermod -L ===>> lock
	usermod -U ===>> unlock then set password
	id behnam
	usermod -g behnam milad
			   group  user
	usermod -G ===>> append
	usermod -aG sudo behnam ===>> add and ppend
	userdel -r ===>> remove home directory
	sla 5/9
	dowtown
	userdel -f ===>> delete all file
	groupadd
	group /etc/group
	user /etc/passwd
	sudoers /etc/sudoers
	password /etc/shadow
	chage -l behnam
	getent passwd behnam ===>> like grep
	vim /etc/crontab
	crontab -a
	at 15:30
	atq
	atrm
	vim /etc/sysctl.conf ===>> linx as router
	vim /etc/cron.allow
	vim /etc/cron.deny
	vim /etc/at.allow
	vim /etc/at.deny
	date +%Y -%m -%d -%H -%M:%s
	timedatectl set-timezone
	tzselect Asia/Tehran
	locale
	dpkg-reconfigure locales
	hwclock ===>> use clock bios
	shift + ctrl + v ===>> this is for markdown
	```
	ls -l
	```
	put command bettwen ``` 
	tail -f /var/log/syslog
	journalctl -f
	cluster
	journalctl -f | grep -v sda
	vim /etc/nginx.conf

	promoteos
	ghrafano
	alert manager 
	log gather
	stack over flow

	log genaration
		logger local1.warning this is test
		logger local1.error this is test
		logger local1.emergency this is test
	
	do-release-upgrade
	curl "link"

	NAT ===>> network address translation
	mask ===>> in ip private if it wants got out
	cat /etc/services ===>> show port
	ifconfig -s ===>> summery
	ifconfig -a ===>> all
	ifconfig ens37 192.168.1.100
	ifconfig ens37 192.168.1.100
	ifconfig ens37 netmask 255.255.255.0
	route -n
	route add default gw 192.168.1.110
	route del default gw 192.168.1.110
	ip address show
	ip addr add 192.168.1.150/24 dev ens37
	ip addr del 192.168.1.150/24 dev ens37
	ip link set ens37 down
	ip link set ens37 up
	ip link show
	ip route show
	ip route add 10.0.0.10 via 192.168.1.150 dev ens37
	ip route add default via 192.168.1.100
	ip route del default via 192.168.1.100
	ping -i 0.5 google.com
	ping -S ens37 8.8.8.8
	ping -I ens37 8.8.8.8

	/etc/netplan/*.yaml
	netplan try
	/etc/network/interfaces
	systemctl restart network.service
	/etc/sysconfig/network-scripts/ifcfg-ens37
	systectl restart network

	traceroute 8.8.8.8 or google.com
	tracepath 8.8.8.8 or google.com
	mtr 8.8.8.8 or google.com

	netstat -atulnp ===>> show connection
	telnet 192.168.1.100
	telnet google.com 80 ===>> this is important
	netcat -L 8090 ===>> nc
	telnet 192.168.1.100 8090
	nslookup @8.8.8.8 google.com
	dig google.com
	/etc/nsswitch.conf
	diff file1 file2
	nmap 192.168.1.100
