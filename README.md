Hello all :) 

In this exercise I was able to install nginx in an Ansible script. 

# Ansible Playbook: Install Apache Web Server

This Ansible playbook installs the Nginx Web server  on a specified Ubuntu host.

# Author Slobodan Milojevic 

I created a directory called ansible project with the command mkdir ansibleproject. 

In that same directory, I created 3 files.

touch ansible.cfg 

touch inventory.init

touch webserver.yml

Here are the images : 
<img width="754" height="254" alt="image" src="https://github.com/user-attachments/assets/2b9677e9-8519-497b-b322-f46aa5bf4160" />
<img width="950" height="76" alt="image" src="https://github.com/user-attachments/assets/1513e903-bd81-4dad-82b7-a5cb7a7e9ef9" />
<img width="1100" height="152" alt="image" src="https://github.com/user-attachments/assets/f1b7ad45-609d-4af5-b6bb-acd4261687b9" />

<img width="1055" height="177" alt="image" src="https://github.com/user-attachments/assets/3128ffb2-c026-4f78-b5ae-e113f5e0bbc9" />
<img width="1098" height="504" alt="image" src="https://github.com/user-attachments/assets/0f39611c-b4ad-4361-9291-0586262e7b73" />
<img width="1093" height="375" alt="image" src="https://github.com/user-attachments/assets/79064922-b908-4015-9d0c-3e56557c83b0" />
<img width="517" height="111" alt="image" src="https://github.com/user-attachments/assets/84fe812d-803f-45fd-ae2c-62f6de5c23b8" />

# Descriptiom # 
#!/bin/bash 
-So this is an exercise how to install nginx or apache ( in this case nginx ) with ansible automation. 


---

## Description

- Connects to the host at IP `192.168.1.29` using the user `sloba`.
- Uses `sudo` privileges (`become: yes`).
- Updates the package cache.
- Installs the `apache2` package to ensure Apache is present.

1. Make sure you have Ansible installed on your control machine.
2. Ensure you have SSH access to the target host (`192.168.1.29`) as user `sloba`.
3.  I Run the playbook with : 

ansible-playbook -i 192.168.1.29, install-apache.yml

# Author # 
Slobodan Milojevic 
