# Project-1
[java]
10.0.3.235 ansible_user=ec2-user ansible_ssh_private_key_file=~/.ssh/ec2.pem ansible_ssh_common_args='-o ProxyJump=ec2-user@3.144.90.245'
10.0.4.127 ansible_user=ec2-user ansible_ssh_private_key_file=~/.ssh/ec2.pem ansible_ssh_common_args='-o ProxyJump=ec2-user@3.144.90.86'


[nginx]
3.144.90.245 ansible_user=ec2-user ansible_ssh_private_key_file=~/.ssh/ec2.pem
18.221.224.86 ansible_user=ec2-user ansible_ssh_private_key_file=~/.ssh/ec2.pem
