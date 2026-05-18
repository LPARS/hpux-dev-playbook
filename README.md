# Ansible Playbook: HP-UX

This playbook installs and configures my HP-UX infrastructure from the ground up.

These roles have been developed and verified against the following configuration:

* **OS:** HP-UX 11i v3 (B.11.31)
* **Release:** Data Center Operating Environment (DCOE) - May 2025
* **Architecture:** Itanium (IA64)
* **Python:** 3.11.14

Technically, if you're using a recent enough version of 11i v3, it should work on PA-RISC hosts as well
given you have Python 2 installed and a modern version of OpenSSH alongside it. If you want to attempt it,
see [the README in the ansible-9.13-setup directory](ansible-9.13-setup/README.md).
