# Ansible Playbook: HP-UX

This playbook installs and configures my HP-UX infrastructure from the ground up.

## Requirements:

* **OS:** HP-UX 11i v3 (B.11.31) on Itanium (IA64).
* **Python:** Ansible requires Python 3. See the [HP-UX Porting and Archive Centre](http://hpux.connect.org.uk)
for compatible Python packages.

> **Note:** Although modern Ansible requires Python 3, older versions supported Python 2. It is possible to use 
> this playbook on PA-RISC hosts, given the latest version of Python supported on them is Python 2. 
> If you have Python 2 and a modern version of OpenSSH installed and want to attempt this, see 
> [the README in the ansible-9.13-setup directory](ansible-9.13-setup/README.md).

## License

MIT
