# linux old

	uname
    whoami
    stat file1
   	ls ???
   	yes > file1
	sed -i "21i nameserver 8.8.8.8" resolv.conf ===>> add new line
    sed -i "21d" resolv.conf ===>> delete line
    echo " " > file
    tr
    cli ===>> command line
    top
    free
    uptie
    renice -n 19 ID
    regular expression
    regex
    sed -r "s/^a/b/g" file1
    jobs
    nohub
    nohub ping 4.2.2.4
    ps -ef | grep sleep
    ps -aux
    ps -aux | gresp sleep
    dd if=/dev/zero of=1g.test bs=100M count=1
    file ===>> jens file
    gzip
    gunzip
    bzip2
    bunzip2
    split -l2 namefile ===>> khat
    split -b40 namefile ===>> hajm
    
    bash complision
    grep -n ===>> number
    grep -v ===>> baraks neshon mide
    mkdir \ \ ===>> directory with out name
    mkdir \\ 
    ^$ ===>> show enter line
    sed 's/^$/d' ===>> delete empty line
    vim ===>> ctrl + r ===>> redo
    
    vmstat ===>> show memory usage
    free ===>> show memory usage
    cat /etc/services ===>> show all protocol and port
    groups ===>> show your group
    group mems ===>> hamgrohiyato neshon mide
    
    chmod 777 -R /media ===>> zir majmoeharo ham permision taghir mide
    /etc/sysconfig/network-scripts
    sytemctl restart network
    
    subnet
    netmask
    
    ip link set ens37 up
    ip link set ens37 down
    ip link set ens37 address (mac address) ===>> change mac iddress
    dhclient
    dhclient -v ens37
    dhclient -r ===>> remove configuration
    ip address add 192.168.1.100/24 dev ens37
    ip route default via 192.168.1.1 dev ens37
    ip address flush dev ens37ip neigh show
    ARP
    ifdown ens37
    ifup eens37
    	
    cd /etc/sysconfig/network-scripts
        TYPE=Ethernet
        BOOTPROTO=STATIC
        NAME=ens37
        DEVICE=ens37
        ONBOOT=yes
        IPDDR=192.168.1.100
        NETMASK=255.255.255.0
        GATEWAY=192.168.1.1
        DNS1=8.8.8.8
        DNS2=4.2.2.4
    		
	network is unreachable ===>> biron nemire
	destination host unreachable ===>> biron mire vali nemirese
	
	DHCP ===>> Dinamic Host Configuration Protocol
	ping 
	mtr
	mtr 4.2.2.4
	mtr google.com
	net-tools
	traceroute
	tracepath
	netstat -ntulp
	mtu

    ping 8.8.8.8 ===>> ip resolv mikone
	ping google.com ===>> dns moshkel dare

    task
    process
    service
    socket
    	
    systemctl cat ssh
    	
    /usr/bin/systemd/system
    systemctl deamon-reload ===>> command balaiero paiene emal mikone
    /etc/systemd/system
    
    systemctl get-defalt
    log command
        tail -f /var/log/messages
    /var/log/secure ===>> this is for security
    dmesg
    journalctl -xe ===>> show all logs or better than systemctl more information
    last ===>> show log users
    lastb
    /var/log/wtmp ===>> show log files
    lastlog
		
	telnet ===>> like ssh but old
	ssh root@127.0.0.1 -p 22
	
	manipulate ===>> dast kari kardan
	mkfs -t ext4 /dev/sdb1
	mkfs.xfs
	mount
	mount /dev/sdb1 /tmp
	umount /dev/sdb1
	umaount /tmp
	/dev/vg01/lv01
	/dev/mapper/vg01-lv01
	resize2fs /dev/mapper/vg01-lv01 ===>> excute resize
	e2fsck -f /dev/sdb1 ===>> show super block
	xfs_growfs /dev/sdb1
	
	
important for ssh
	setenfore 1 ===>> on
	setenfore 0 ===>> of
	before systemctl restart ssh
	getenforce ===>> show
	selinux ===>> this is help for hacker
	vim /etc/selinux/config
		SELINUX=disable
    	iptables -F ===>> flush iptables
    	ssh-keygen
    	ssh-copy-id behnam@192.168.1.100
    	
    	
    	/etc/ssh/sshd_config
    	Hostkey ===>> you can change directory
    	loglevel VERBOSE ===>> more information about log
    	authorizekysfile .ssh/authorized-key ===>> you can change it
    	gssapiauthication no
    	allowagent forwarding no
    	allowtcp forwarding no
    	useDNS no
    	
    	tail -f /var/log/secure
    	w
    	
fail2ban
	iptable -nL
	cd /etc/fail2ban
		jail.conf
			[sshd]
			enabled = true
			[INCLUDEs]
			[DEFAULT]
			gnorep=127.0.0.1
			bantime = 15 seconds
			findtime = 10 seconds
    			maxretry = 3 seconds
    			[sshd]
    				port = 3122
			[sshd-addos]
				port = 3122
    			[dropbear]
    				port = 3122
			[selinux-ssh]
    				port = 3122
			
		systectl enable fail2ban
		systectl start fail2ban
		
apache
	centos httpd ===>> apache
	/etc/httpd ===>> config fiel
	grep -v "^#" ===>> don't show # at start
	
    	
    	
    	
    	
    	
    	
    	
    	
    	