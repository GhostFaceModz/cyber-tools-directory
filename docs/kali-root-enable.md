# Kali Root Enable

## Description
Enable root account on Kali Linux permanently for SSH, GNOME, and KDE logins.

## Source
- https://www.kali.org/docs/general-use/enabling-root/

## Commands
```bash
# Set root password
sudo passwd
# (enter password for kali user, then new root password)

# Install Kali root login package
sudo apt -y install kali-root-login

# Enable root SSH login
sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/' /etc/ssh/sshd_config
sudo systemctl restart ssh
```
