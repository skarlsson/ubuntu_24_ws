# README #

```
sudo apt -y update
sudo apt-get -y install ssh ansible git aptitude wget unzip
wget https://github.com/skarlsson/ubuntu_24_ws/archive/main.zip
unzip main.zip
cd ubuntu_24_ws-main
```

```
ansible-playbook -i "localhost," -c local initial-ubuntu.yml -u $USER --ask-become-pass 
```

###### if you nned cuda a reboot is nessesary to load the new driver
```
nvidia-smi 
Fri Dec 25 16:49:12 2015
+------------------------------------------------------+
| NVIDIA-SMI 352.63     Driver Version: 352.63         |
|-------------------------------+----------------------+
```


