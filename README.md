```nano /etc/network/interfaces```

### This file describes the network interfaces available on your system
### and how to activate them. For more information, see interfaces(5).

source /etc/network/interfaces.d/*

# The loopback network interface
auto lo
iface lo inet loopback

# The primary network interface
allow-hotplug enp5s0
iface enp5s0 inet static
address 静态IP
netmask 子网掩码
gateway 网关
dns-nameserver DNS服务
```
