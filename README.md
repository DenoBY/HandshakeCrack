## HandshakeCrack
The module automates work with service https://www.onlinehashcrack.com

![alt text](https://i.ibb.co/dQSp27s/Handshake-Crack.png)

#### Functional:
- WIFI / WPA(2) password recover
- PCAP and CAP dump file to HCCAPX - instantly

**Device:** Tetra / NANO

**Official topics for discussions:**
```
https://forums.hak5.org/topic/45362-module-handshakecrack/
https://codeby.net/threads/5-wifi-pineapple-handshakecrack.66700/
```

**Module installation for Tetra:**

```
opkg update && opkg install git git-http
cd /pineapple/modules/
git clone https://github.com/n3d-b0y/HandshakeCrack.git HandshakeCrack
chmod +x -R /pineapple/modules/HandshakeCrack/scripts
```

**Module installation for NANO:**
```
opkg update && opkg --dest sd install install git git-http
cd /sd/modules/
git clone https://github.com/n3d-b0y/HandshakeCrack.git HandshakeCrack
chmod +x -R /sd/modules/HandshakeCrack/scripts
```