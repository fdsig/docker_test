# A repo for testing docker

using code from the amazing [Liz Rice](https://github.com/lizrice/containers-from-scratch)

Becasue its always nice to learn new tools in their native language even if only at quite a surface level. 

I copied out manually for my own leanring however origional code is available from linked repository above. The onely differeces are imports which allow code to run on go install on ubuntu 18.06.
bash commands for copying a linux file system to run 
'''bash
sudo apt-get update
sudo apt-get istall golang-go

'''
'''bash
rsync -aAXv / --exclude={"/dev/*","/proc/*","/sys/*","/tmp/*","/run/*","/mnt/*","/media/*","/lost+found","/home/*"} /vagrant/ubuntu-fs
'''

fork bomb to test controle group:

'''
:() { :|: &};:
'''


