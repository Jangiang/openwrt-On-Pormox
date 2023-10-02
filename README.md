# openwrt-On-Pormox
Mở CMD Trong thư mục Chứa Openwrt
scp ./"Openwrt FW.img.gz" root@"ip của máy chủ":/tmp
ssh root@"IP máy chủ"
cd /tmp
ls
gunzip "Openwrt FW.img"
ls
qm importdisk "VM ID" "Openwrt FW.img" local-lvm
>OPITION>Boot Order> Bỏ tích (scis0 ide2)

