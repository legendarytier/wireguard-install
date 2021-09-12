_I have tested this code on Ubuntu 20.04

_Run this command

wget https://git.io/JuiKe -O wireguard-install.sh && bash wireguard-install.sh

_After install completed run this command to see config file

nano /root/'your name'.conf

_You will see like this 

[Interface]
Address = x.x.x.x/24
DNS = 8.8.8.8, 8.8.4.4
PrivateKey = iPp8KmZQzsxxxxxxxxxxxxxxxxxxxxxz9X0OO8ED0A=

[Peer]
PublicKey = 4SJMlcxxxxxxxxxxxxxxxxxxxxxxxxxxxxf2s9nzM=
PresharedKey = dtZgt7SEElxxxxxxxxxxxxxxxxxxxxxxxxxxxe0qICQ6N2w=
AllowedIPs = 0.0.0.0/0, ::/0
Endpoint = x.x.x.xx:51820
PersistentKeepalive = 25

_Copy them all and paste to the client
