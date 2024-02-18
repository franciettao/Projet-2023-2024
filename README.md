# Projet-2023-2024


root@sql:/home/sql# cat /etc/netplan/00-installer-config.yaml
# This is the network config written by 'subiquity'
network:
  ethernets:
    ens33:
      addresses:
      - 192.168.240.240/24
      gateway4: 192.168.240.254
      nameservers:
        addresses:
        - 8.8.8.8
        search: []
  version: 2
