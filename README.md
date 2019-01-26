# linux-distro-setup
Setup Instructions for various Distributions

# Debian 9 Minimal Server

Add remote ssh access and get IP Address
```
apt-get install openssh-server
ip address | grep 'inet ' | grep -v 'lo$'
```

Add sudo
```
apt-get install sudo
usermod -aG sudo <username>
```

Add git
```
apt-get install git
```

Add Python 3 and pip3
```
apt-get install python3-pip
```


# Ubuntu Server 18.04.1 LTS

Add pip3
```
apt-get install python3-pip
```


# Raspberry Pi Strech

Add pip
```
apt-get install python-pip
```

Add git
```
apt-get install git
```
