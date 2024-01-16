command to run: ansible-playbook  -e component=web main.yaml
steps: 
  1. create one ansible_server and attach a IAM role(EC2,R53 full access)
  2. run shell script to create instances(C:\Users\hithe\devops\shell\create_instances.sh)
  3. in ansible_server install ansible(sudo yum install ansible -y)
  