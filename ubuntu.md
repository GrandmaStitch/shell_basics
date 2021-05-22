### ufw

- **Check the status of your firewall**

  `ufw status verbose`

- **Allow the SSH port 22**

  `ufw allow ssh`

- **Allow the HTTP port 80**

  `ufw allow http`

- **Allow a port on tcp listening**

  `ufw allow 8080/tcp`

- **Allow only a specific IP address to connect via SSH port 22**

  `ufw allow from 192.168.1.2 to any port ssh`

- **Allow only a specific network subnet to connect via SSH port 22**

  `ufw allow from 192.168.0.0/24 to any port ssh`

- **To delete your SSH defined rules**

  `ufw delete allow ssh`
  `ufw delete allow from 192.168.1.2 to any port ssh`
  `ufw delete allow from 192.168.0.0/24 to any port ssh`


