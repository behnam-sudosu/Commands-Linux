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
    	
    	
    	
    	
    	
    	
    	
    	
    	