# ansible-linux-report


Run generate_report.yml like below, which will gather facts from hosts in inventory, and then using a template, generate a server_report.html file.
ansible-playbook generate_report.yml -i "localhost,"
