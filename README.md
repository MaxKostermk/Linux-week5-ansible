Linux week 5 eindopdracht

Plaats de twee repositories in Ubuntu

` git clone https://github.com/wildfoxcz/Ansible-WordPress-installation.git
git clone https://github.com/MaxKostermk/linux-week5-ansible.git`

Verplaats dan de roles map

`mv Ansible-WordPress-installation/roles linux-week5-ansible/`

En verplaats dan main.yml naar de nieuwe roles map

`mv linux-week5-ansible/main.yml linux-week5-ansible/roles/mysql/defaults/`

Wachtwoord vault = hoi
