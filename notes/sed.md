# add and delete line with sed
    sed -i '21i nameserver 8.8.8.8' resolv.conf ===>> add line
    sed -i '21d' resolv.conf ===>> delte line