# me-coder
### Share folder linux

```sh
vmware-hgfsclient
// Kiểm tra xem có thư mục được chia sẽ hay ko

// tạo thư mục /mnt/hgfs/ nếu chưa có
sudo mkdir /mnt/hgfs

// mount tất cả thư mục đó
mount -a 

// mount từ host sang /mnt/hgfs/
sudo vmhgfs-fuse .host:/ /mnt/hgfs/ -o allow_other -o uid=1000
```
### install cross compile
```script
tar -xzvf 
PATH=$PATH:/opt/FriendlyARM/toolschain/4.5.1/bin
```
