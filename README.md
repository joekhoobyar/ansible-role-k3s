# ansible-role-k3s

## Overview

Stolen from https://github.com/k3s-io/k3s-ansible, with changes:

- Better support for resource and storage constrained devices (like SBCs)
  - Reasonable defaults for reserving CPU and memory
  - Support separate mounts for k3s and container data
- Use k3s standard systemd service names
- Merge all logic into a single ansible role
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
