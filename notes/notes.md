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

    mix enviorment
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

    MYMOOD=happy
    echo $MYMOOD
    env ===>> motaghayer mahaliro neshon mide
    unset
    set ===>>> motaghayer mahaliro namayesh mide
    uname
    !! ===>> akharin
    !vim
    !?chert? or ctrl + r ===>> ctrl + r aghabaghab mire
    PATH=$PATH:/tmp

    
    ctrl + d ===>> dastoro mibande
    ctrl + c ===>> dastoro miyad biron

    split -l2 namefile ===>> khat
    split -b40 namefile ===>> hajm

    head
    tail
    nl
    cat -n
    sort -n uniq -c -u -d
    cut -f2 -d" " namefile

    sed 's/yes/no/g' namefile
    tr translate

    cp -i ===>> interactive
    cp -b ===>> backup
    ls -L ===>> zir majmoeharo namayesh mide

    find -atime ===>> read
    find -ctime ===>> change
    find -mtime ===>> mohtavaavaz beshe
    -6 ===>> 6 roz ghabl ta be alan
    +6 ===>> 6 roz ghabl tabe ghablesh
    ls ===>> -dils

    file ===>> jens file
    gzip
    gunzip
    bzip2
    bunzip2

    dd if=/dev/zero of=1g.test bs=100M count=1
    
    ls 1> file1
    ls 2> file1
    ls &> file1
    
    /dev/null
    tr ' ' ',' < uses

    jobs
    nohub
    nohub ping 4.2.2.4
    ps -ef | grep sleep
    ps -aux
    ps -aux | gresp sleep

    top
    free
    uptie
    renice -n 19 ID
    regular expression
    regex
    sed -r "s/^a/b/g" file1

    echo " " > file
    tr
    cli ===>> command line
    
    yes > file1
    sed -i "21i nameserver 8.8.8.8" resolv.conf ===>> add new line
    sed -i "21d" resolv.conf ===>> delete line

    stat file1
    ls ???

    vim
        :new /home/behnam/file1
        :!ls
        :tabnew
        :tabnext
        ctrl + w ===>> switch between tab
        vimdiff file1 file2

    !! ===>> excute last command

    mariadb
    mongo
    poskersql
    redis
    cadandra
    kockroch

    uname
    whoami

    sort -k2 file1 ===>> with culeme
    sort -n -k2 file1 ===>> number
    sort -r -n -k2 file1 ===>> reverse





