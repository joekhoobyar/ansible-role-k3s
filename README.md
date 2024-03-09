# ansible-role-k3s

## Overview

Stolen from https://github.com/k3s-io/k3s-ansible, with changes:

- Merge all logic into a single ansible role
- Use k3s standard systemd service names
- Avoid falling back on iptables-legacy:
  - Use iptables-nft for now until we see something break

## Supported Systems

- [X] Debian
- [X] Ubuntu
- [X] Raspberry Pi OS
- [X] Armbian

### Supported arches

- [X] amd64
- [X] arm64
- [X] arm

## License

ansible-role-kernel is Apache 2.0 Licensed
