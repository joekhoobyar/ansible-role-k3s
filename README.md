# ansible-role-k3s

Stolen from https://github.com/k3s-io/k3s-ansible, with changes:

 - Merge all logic into a single ansible role
 - Use k3s standard systemd service names
 - Avoid falling back on iptables-legacy:
   - Use iptables-nft for now until we see something break
