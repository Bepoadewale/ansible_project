# Ansible Realtime project

## Task 1

Create three(3) EC2 instances on AWS using Ansible loops
- 2 Instances with Ubuntu Distribution
- 1 Instance with Centos Distribution

Hint: Use `connection: local` on Ansible Control node.

ansible-playbook ec2_create.yaml --vault-password-file vault.pass

## Task 2

Set up passwordless authentication between Ansible control node and newly created 
instances.

ssh-copy-id -f "-o IdentityFile ~/needed_files/windows-demo.pem" ubuntu@34.201.172.43
ssh ubuntu@34.201.172.43

## Task 3

Automate the shutdown of Ubuntu Instances only using Ansible Conditionals

Hint: Use `when` condition on ansible `gather_facts`






