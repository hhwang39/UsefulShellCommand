# UsefulShellCommand
shell command just for me

## Shell
#### Go back to previous cd location
cd -
#### Run Script
1. Current Directory\
`./script.sh`
2. Different Directory\
`/path1/path2/path3/script.sh`
3. Run Script that runs relative to script's location (copy files ...)\
`cd directory && ./script.sh`
#### grep process by name pattern (full)
`pgrep -lf pattern` (-l pattern, -f full command)
#### last returned value (status 0: success otherwise: fail)
$? -> last returned value\
ex: `cat "hello world" | grep "hello" > /dev/null`\
echo $?
#### Mount Driver
Mount\
`sudo mount /dev/sdb1 directory`\
Unmount\
`sudo umount directory`

#### run dhcp on network interface
`sudo ifconfig eth0 0.0.0.0 0.0.0.0 && sudo dhclient`
`sudo killall dhclient && sudo ifconfig eth0 10.0.1.22 netmask 255.255.255.0`
## Jenkins

## SSH
Connection Reset By [ip] port 22\
`sudo rm /etc/ssh/ssh_host_* && sudo dpkg-reconfigure openssh-server`\
Run sshd
1. `sudo service sshd start`
2. `sudo systemctl start sshd.service`

