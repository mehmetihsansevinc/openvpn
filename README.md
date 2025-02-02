# OpenVPN
OpenVPN installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora.

### Installation

The virtual machine (AWS EC2, Azure VM, Huawei ECS) need to just have a private IP with only one network interface. No need to use NAT Gateway. Consider your Routing Table rules.
Elastic IP will be the Public IP gateway of the VM.

`Internet  ---> Elastic IP ---> Private Interface of VM`

Run the script and follow the assistant:

`wget wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

You can run it to add more users, remove some of them or uninstall WireGuard.
