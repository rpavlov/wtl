# Use

    ansible-playbook -i provisioning/wtl_inventory provisioning/wtl.yml --ask-become-pass

# Info

## IP
* eth0 ip is 192.168.1.17

## SSL Cert gen

    sudo certbot certonly --manual --preferred-challenges dns

# Todo

* Hardening
  * Deploy user
* Weechat relay
* Tor exit node
