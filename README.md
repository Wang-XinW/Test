# Test
This is a test programme
!/bin/bash
cd /root/kcptun/
./server_linux_amd64 -l :29900 -t 45.32.221.41:36000 -key test -mtu 1400 -sndwnd 2048 -rcvwnd 2048 -mode fast2 > kcptun.log 2>&1 &
echo "Kcptun started"
