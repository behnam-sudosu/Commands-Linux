# notes
    blue screne
    discountinu

    change log direction
    vim /etc/rsyslog.d/50..
        cron .*

    zabix
    promethos
    grafana

    ARM ===>> phone
    x86-64 ===>> pc

    next engineering
    up and run
    redundant
    cloude provider 
    ISP
    ELK ===>> elastic search logstash kibana

    database
    oracle
    mssql 

    mix inviorment
    intigerate ===>> ba ham yeki kardan

    SRE ===>> site reliable engineer
    vmware esxi
    /etc/passwd ===>> you can see all user

    application ===>> deploy
    replicate ===>> backup
    gluster cpu
    network ===>> assine = dadan
    traphorm ===>> infrustructure as code
    nat ===>> network address translation
    detect ===>> peida kardan
    packet tracer
    web server ===>> nginx
    web service ===>> web site 

    askicode
    absulute path
    cd -
    blkid
    uuid
    date +%s
    proc
    	cpuinfo
    	meminfo
    	uptime
        file systems
    tmp
	sys

    tac
    uptime
    dev ===>> device
    ls /dev | grep sda
    
    lsusb
    lscpu ===>> see online or ofline
    lsusb -v ===>> more information
    lshw

    lsb-release -a
    cat /etc/os-release
    
    command sub-command switch option
    
    ls -ltrha
    AUTHOR
    ping -c 3 8.8.8.8
    ls --help

    lsmod
        remove
        install
        disable
        enable
    modprobe
    proc/modules
    metadata
    supper block
    boot loader
    component ===>> pishniaz
    
    /var/log/syslog ===>> show all logs
    /var/log/messages ===>> show all logs
    dmesg ===>> kernel ring buffer

    dhclient

    /etc/sysconfig/network-script/ifcfg-ens33
        onboot = yes
    
    openssh-server
    ajormicrosoft
    
    dpkg = apt
    rpm = yum

    udevadmin monitor
    variable ===>> hw many history save

    /usr/bin ===>> command
    /usr/sbin ===>> command

    replica ===>> backup

    /var/log
        syslog ===>> system log
        kern.log ===>> kernel log
        auth.log ===>> user log

    cat /etc/default/grub
    /etc/init.d ===>> service are here
    systemctl
        stop
        start
        restart
        reload
        enable
        disable
    systemctl set-default
    systemctl get-default
    systemctl is-active ssh
    systemctl is-inactive ssh
    systemctl is-enabled ssh
    systemctl is-disabled ssh

    service
        *.service
    /etc/systemd/system
    /usr/lib/systemd/system
    service ufw status
    netcat ===>> nc
    nc -l 8090
    
    lsblk
    swapon -s
    swapoff /swap.img
    swapon /swap.img
    
    pv ===>> pvdisplay
    vg ===>> vgdisplay
    lv ===>> lvdisplay

    raid 1 or mirror
    duplicate ===>> have two place

    grub-mkconfig ===>> reganarate
    which ls ===>> where is save file
    echo $PATH ===>> show direction save command
    ldd /user/bin/ls ===>> show list library dependency
    dependence resolve
    pkgs.org
    wget
    dpkg -i

    halt ===>> poweroff
    /etc/init.d/ufw restart ===>> use old sysadmin
    backward compatible
    
    rsyslog ===>> show logs directory
    rsync ===>> scp

    lib ===>> mitoni masir librery bedi
    ldd
    /etc/ld.co-conf.d/ ===>> all library are here

    ldconfig ===>> more information

    apt remove zip ===>> dpkg -r zip
    atp purge zip ===>> dpkg -p zip
    apt-cache search firefox

    netcat ===>> nc
    telnet ===>> monitor network

    yum === dnf
    yum check-update ===>> update
    yum update ===>> upgrade

    IAC ===>> infrustructure as code

    yum install epel-release ===>> more repository
    yum history ===>> who install and uninstall package

    plug ===>> vasl kardan

    /sys ===>> HAL
    /proc ===>> kernel
    /proc/sys/net/ipv
        IP-forward ===>> you can change your linux to router

    lsmod modules kernel load
    rmmod
    modprobe -r (name) ===>> remove
    modprobe (name) ===>> install
    /etc/modules ===>> if you want to load every time
    /etc/modprobe
        *.conf
    
    dmesg ===>> show all
    /var/log/dmsg ===>> kernel ring buffer
    /var/log/meessages ===>> centos
    /var/log/syslog ===>> ubuntu

    ftp server ===>> file transfer protocol ===>> protocoli ke mitone file jabeja kone
    nfs ===>> network file system ===>> eshterak gozari file az tarigh shabake
    smb ===>> windows

    /etc/init.d ===>> all service is here
    RC ===>> link be ine
    /sbin/init
    
    HALT ===>> system goes down

    upstart ===>> service, ssh stop
    systemd
    /etc/systemd/system
    systemctl stop ssh
    service ssh stop
    /etc/init.d

    primary
    extended
    logical
    parted
    MBR ===>> master boot record
    chain loading
    grub-install /dev/sdb1
    grub-install /dev/sdb
    grub-mkconfig > /boot/grub/grub.cfg
    update-grub

    ch ~/.local/share/keyrings
        rm *.keyrings
    
    sudo apt-mark hold (name)
    sudo apt-mark unhold (name)

    LD_LIBRARY_PATH
    export ===>> motaghayer mohitiro namayesh mide

    export LD_LIBRARY_PATH=/home/behnam/lib

    yum upgrade

    stdin
    stdout
    stderr

    cat .profile
    cat /etc/profile
    cat /etc/bash.bashrc
    cat .bashrc

    ls ; echo dine
    ||
    &&
    echo $PATH
    echo $SHELL
    echo $$
    echo $?

    PATH
    type whereis which
    #!/bin/bash

    PATH=$PATH:/tmp

    
        