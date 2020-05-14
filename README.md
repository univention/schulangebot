# Schulangebot
https://help.univention.com/t/schulangebot-powered-by-ucs-school-hosted-by-hostern/14593

# Requirments

- UCS ISO or Appliance Image (KVM, VMWare, VirtualBox, ec2) - https://www.univention.de/download/download-ucs/
- UCS ISO needs to be installed an snapshotted and set to DHCP for the system
- UCS is configured to use DHCP for the system, make sure the instance gets a valid network address
- Internet access

# Configuration

- In vars/main.yml -> Public Domain

# Run

ansible-playbook site.yaml -i hosts-file
