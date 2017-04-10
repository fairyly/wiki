# Setup CentOS


使用 `CentOS-7-x86_64-Minimal-1611.iso` 安装后的配置流程如下

### Update system

    sudo yum update -y

### Install missing softwares

    sudo yum install -y ifconfig vim tmux

### Configure hostname

    sudo vim /etc/hosts
    sudo vim /etc/hostname
    sudo hostname hostname

### Configure SSH server

[[SSH]]

### EPEL Repo

    sudo yum install epel-release

### CPU benchmark

    sudo yum install sysbench lm_sensors