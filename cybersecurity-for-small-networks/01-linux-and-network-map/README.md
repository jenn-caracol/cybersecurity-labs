
# Chapter 1 – Getting Started with a Base Linux System and Network Map

## 🎯 Objective
- Setup Ubuntu virtual machine to use throughout these labs
- Create a network map


### 💡 Skills Practiced
- Virtual machine creation
- Linux installation and system hardening
- Secure SSH configuration
- Network topology mapping

### 🛠️ Tools Used
- Ubuntu 24.04.2 LTS
- VMware Workstation 17 Pro
- OpenSSH
- Draw.io for network map

<!--
## 🧪 Lab Steps
1. Created an Ubuntu VM using VirtualBox.
2. Updated system and installed essential packages: `sudo apt update && sudo apt upgrade`.
3. Configured SSH key-based login and disabled password auth.
4. Captured current network settings using `ip a` and `ip route`.
5. Drew a basic network map including VM, host, and router relationships.
-->

### 📸 Screenshots or Code Snippets
![Network Map](../01-linux-and-network-map/generic-home-network-map.jpg)

<!--
```bash
sudo apt install openssh-server
ssh-keygen -t rsa
sudo ufw allow ssh
```
-->
<!--
### 📘 Reflections & What I Learned

- Learned the difference between bridged and NAT networking in VMs.
- SSH key login is significantly more secure than passwords.
- Creating a visual network map gave me clarity on how devices are routed.

-->
<!--
### 🔗 References

- [Ubuntu Server Docs](https://ubuntu.com/server/docs)
- [OpenSSH Manual](https://man.openbsd.org/ssh)
-->
<!--
## 🧠 Next Steps

- Add firewall rules and VLAN separation (in Chapter 2).
- Try creating the same setup in a cloud provider like AWS or Linode.
-->
