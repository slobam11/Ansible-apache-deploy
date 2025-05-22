Hello all :) 

# Ansible Playbook: Install Apache Web Server

This Ansible playbook installs the Apache web server on a specified Ubuntu host.

---

## Description

- Connects to the host at IP `192.168.1.131` using the user `sloba`.
- Uses `sudo` privileges (`become: yes`).
- Updates the package cache.
- Installs the `apache2` package to ensure Apache is present.

---

## Usage

1. Make sure you have Ansible installed on your control machine.
2. Ensure you have SSH access to the target host (`192.168.1.131`) as user `sloba`.
3.  I Run the playbook with : 

ansible-playbook -i 192.168.1.131, install-apache.yml
