# Ansible Playbook: HP-UX

This playbook installs and configures my HP-UX infrastructure from the ground up.

## Requirements:

* **OS:** HP-UX 11i v3 (B.11.31) on Itanium (IA64).
* **Python:** Ansible requires Python 3. See the [HP-UX Porting and Archive Centre](http://hpux.connect.org.uk)
for compatible Python packages.

> ** Note:** Technically, if you're using a recent enough version of 11i v3, it should work on PA-RISC hosts as well
> given you have Python 2 installed and a modern version of OpenSSH alongside it. If you want to attempt it,
> see [the README in the ansible-9.13-setup directory](ansible-9.13-setup/README.md).

## License

MIT
