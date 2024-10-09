# Setup SSH vpn server and client

Instructions:
- ansible-playbook -i inventory.ini vpn_client.yml --ask-pass --ask-become-pass
- ansible-playbook -i inventory.ini vpn_server.yml
