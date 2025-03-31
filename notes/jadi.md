# notes from jadi lpic1
    /etc/init.d ===>> you can see your service here
    /etc/systemd/system ===>> you can see your sevice here
    /etc/rc ===>> you can see links
    
    modprobe -r ===>> remove moduls
    rmmod ===>> remove moduls
    lsmod ===>> see moduls
    modprob ===>> install moduls
    
    dmesg ===>> command show log
    /var/log/dmesg ===>> show log kernel ring buffer only
    /var/log/messages ===>> show all log in centos
    /var/log/syslog ===>> show all log in debian

    chain load
    promp ===>> stay and do nothin until i said what you have to do

    grub-install /dev/sdb1 ===>> install grub
    grub-mkconfig ===>> make grub
    /boot/grub/grub.conf

    whereis ls
        /usr/bin/ls
    ldd /usr/bin/ls
    ldconfig ===>> command re cach
    /etc/ld.so.cach ===>> cach library
    /etc/ld.so.conf
    locate libudev.so.1

    export ===>> motagheir mohiti
    export LD_LIBRARY_PATH=/home/behnam:/home/milad
    PATH=$PATH:/tmp

    opt ===>> third party
    dpkg-reconfigure tzdata ===>> command not found

    sudo apt clean ===>> clean archives file
    rm -rf /var/cach/apt/archives/*
    sudo apt autoclean ===>> clear old 
    sudo apt --fix-broken install ===>> install library and dipendance
    sudo apt install -f ===>> install library and dipendance

    yum update ===>> upgrade
    yum check-update ===>> update
    exec ls ===>> close shell

    env
    echo $USER
    echo $UID
    echo $HOME
    echo $SHELL
    echo $$
    echo $?
    echo $HISTFILE .bash_history
    echo $HISTSIZE 1000
    echo $PATH
    MYMOOD=happy
    echo $MYMOOD
    !! ===>> execute last command
    !vim
    !?vim?
    ctrl + r ===>> search and go back 
    type ping ===>> what is ping
    which
    whereis

    cat /etc/passwd ===>> you can see your users
    cat /etc/shadow ===>> you can see hash password
    cat /etc/group ===>> you can see your groups

    #!/bin/bash ===>> start file that make to executeble

    split -l3
    split -b40

    journalctl -xe ===>> show log

    rsync nad scp
    RHEL
    incognito

    scp -P4000 file1 ubuntu@192.168.1.100:/home/ubuntu

    uniq -c ===>> count
    uniq -u ===>> uniq
    uniq -d ===>> diff
    sort -n ===>> numeric
    cut -f2 -d"-" file1
    sed 's/A/B/g' file1
    tr '-' '_'

    touch ===>> change type stamp
    touch -r file1 file2 ===>> change time file1 to file2

    find -name "f?"
    find -type d ===>> directory
    find -type f ===>> file
    find -size 100B
    find -size +1G -1G
    find -size 0 ===>> empty file
    find -atime -6 ===>> access time (like read)
    find -ctime +6 ===>> file changed (copy, chnage user, ....)
    find -mtime -6 ===>> file content chaged

    file ===>> show material file or directory

    dd if=ubuntu.iso of=/dev/sdb bs=4096
    dd if=/dev/zero of=test bs=100M cont=1 ===>> make file 100M
    
    /dev/null
    /dev/zero
    /dev/random

    ls 1> file1 ===>> stdout
    ls 2> file1 ===>> error
    ls x* m* 1> output 2> error
    ls x* m* &> output
    ls x* m* 1> output 2>&1







