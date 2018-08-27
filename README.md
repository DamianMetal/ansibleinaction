ansible ec2-18-223-116-32.us-east-2.compute.amazonaws.com -m setup --> facts variable
ansible-playbook -i inventory.cfg --limit ec2-18-223-116-32.us-east-2.compute.amazonaws.com ntpPlaybook.yml --> run the ntpRole
