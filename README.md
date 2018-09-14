# UsefulShellCommand
shell command just for me

## Shell
#### Go back to previous cd location
cd -
#### Run Script
1. Current Directory: "./script.sh"
2. Different Directory "/path1/path2/path3/script.sh"
#### Mount Driver
Mount\
`sudo mount /dev/sdb1 directory`\
Unmount\
`sudo umount directory`

## Jenkins

## SSH
Connection Reset By [ip] port 22\
`sudo rm /etc/ssh/ssh_host_* && sudo dpkg-reconfigure openssh-server`\
Run sshd
1. `sudo service sshd start`
2. `sudo systemctl start sshd.service`

