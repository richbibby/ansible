# ansible
Random ansible playbooks, mainly for Cisco IOS and Aireos

#to run a playbook use --extra-vars to specfify the target host

ansible-playbook verify_dmvpn.yml --extra-vars "target=r1"

OR 

ansible-playbook verify_dmvpn.yml --extra-vars "target=routers"
