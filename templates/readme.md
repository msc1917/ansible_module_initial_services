# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "initial_02_services"
Standard-Einrichtungsschritte für jeden Host: Einrichtung der Software-Services.

## Verzeichnis "templates"
Jinja2-Templates, welche von der Rolle benötigt werden könnten

## Templates:
* **avahi/sftp-ssh.service.j2:**
* **avahi/ssh.service.j2:**
* **dhcp/dhcpd.conf.j2:**
* **dns/domain.list.j2:**
* **dns/domain.zone.j2:**
* **dns/domain.zone.simple.j2:**
* **dns/in-addr.arpa.zone.j2:**
* **dns/in-addr.arpa.zone.simple.j2:**
* **dns/named.conf.j2:**
* **ldap/systems.ldif.j2:**
* **ldap/users.ldif.j2:**
* **ssh/sshd_config.j2:**
* **ssh/sshd_config.jumphost.backup.j2:**
* **ssh/sshd_config.jumphost.j2:**
* **xrdp/sesman.ini.j2:**
* **xrdp/xorg.conf.j2:**
* **xrdp/xrdp.ini.j2:**
