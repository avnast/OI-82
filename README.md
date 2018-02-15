# OI-82

This playbook launches EC2 instance and install Docker and Jenkins to it.

Usage:
  1) adjust values in params.yml
  2) run 'ansible-playbook playbook.yml'
  
Requirements:
  - boto, boto3, python >= 2.6 (required by Ansible modules ec2 and ec2_group)
  - valid AWS API credentials
  - Internet connectivity for launched instance
