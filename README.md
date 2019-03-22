# multiinstaller


SSH+Dropbear+Squid3+Stunnel+OpenVPN+Shadowsocks with Cloak installer for Ubuntu 16.04

This script will let you setup your own secure Tunneling server in just a few seconds.


## Usage

### KVM Server
First, get the script and make it executable :

```bash
curl -O https://raw.githubusercontent.com/malikshi/IPTUNNELS/master/kvm.sh
chmod +x kvm.sh
```

Then run it :

```sh
./kvm.sh
```


### OpenVZ Server
First, get the script and make it executable :

```bash
curl -O https://raw.githubusercontent.com/malikshi/IPTUNNELS/master/openvz.sh
chmod +x openvz.sh
```

Then run it :

```sh
./openvz.sh
```


# Log Installation
log- installation will be stored in /root/log-install.txt and can be accessed via webserver http://IP:81/log-install.txt

Other Lisence :
[Angristan](https://raw.githubusercontent.com/Angristan/openvpn-install/master/LICENSE)
[Nyr](https://github.com/Nyr/openvpn-install/blob/master/LICENSE.txt)
[Stunnel](https://www.stunnel.org/index.html)
[Dropbear](https://matt.ucc.asn.au/dropbear/dropbear.html)
[Shadowsocks](https://shadowsocks.org)
[Cloak](https://github.com/cbeuw/Cloak/blob/master/LICENSE)
