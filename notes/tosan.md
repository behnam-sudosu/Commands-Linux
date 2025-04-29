# tosan
    Applicarion
    Dbus
    Hal ===>> Hardware Abstraction Layer
    Udev
    Kernel
    unity
    cat /proc/mount
    vim /etc/sysct.conf
        net.ipv4.ip-Forward=1
    lsmod ===>> show all
    rmmod (name module) ===>> remove
    modprobe (name module) ===>> install
    vim /etc/modules
    vim /etc/modprobe.d
    dmesg ===>> show all
    vim /var/log/dmesg ===>> only boot
    inittab
    init.d ===>> all service and scripts are here
    runlevel 0 ===>> turn off
    runlevel 1 ===>> single user
    runlevel 2 ===>> multi user
    runlevel 3 ===>> multi user with network
    runlevel 4 ===>> no used
    runlevel 5 ===>> graphical mod
    runlevel 6 ===>> restart
    /etc/init.d/rc ===>> all service and script
    ./network-manager status
    ln -s ../init.d/bluetooth s021blue
    rm
    filesystem (local, network)
                ext4     nfs
    /boot/grub/grub.cfg
    /etc/default/grub
    /etc/grub.d
    grub-mkconfig
    grub-install
    update-grub
    dd of=/dev/sda of=/root/mbr.backup bs=512 count=1
    LD_LIBRARY_PATH ===>> this is for library
    export LD_LIBRARY_PATH:/hoem/behnam/lib
    /usr/local/lib
    ldd ===>> show the pfogram use library
    ldconfig ===>> update file cache
    ld.so.cache
    ls.so.conf
    /usr/lib
    /usr/local/lib
    /usr/bin
    /usr/sbin
    export ===>> show invirement variable
    dpkg-reconfigure firefox
    yumdownloader --resolve openssh-clients
    /etc/profile.d/*.sh ===>> scripts
    /etc/bash.bashrc
    .profile
    .bashrc
    cat > jimbo
        ifconfig
    ./jimbo
    env
        PATH=/
    FIRST=salam
    export FIRST
    env
    PATH=$PATH:/home/behnam ===>> don't need set aliasses
    .bashrc ===>> change it
    unset FIRST
    apropos ===>> like man
    mv -i ===>> ask befor
    cp -i ===>> ask befor
    mv -v ===>> more information
    mv -v ===>> more information
    rm -i ===>> ask befor
    file * ===>> show material all file and directory
    find -atime +2
    find -ctime +2
    find -mtime +2
    ls 1> list.txt ===>> output
    ls 2> list.txt ===>> error
    ls *.mp3 > mp3 2> errormp4
    2.&1
    nohub sleep 444 & ===>> you can close shell
    ps -aux
    