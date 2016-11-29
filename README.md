Awscli
=========

Role for install awscli.

Role Variables
--------------

aws_cli_user: 'root'
aws_output_format: 'json'
aws_region: 'ap-southeast-2'
aws_access_key_id: 'YOUR_ACCESS_KEY_ID'
aws_secret_access_key: 'YOUR_SECRET_ACCESS_KEY'
awscli_version: 1.10.45


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: awscli, aws_access_key_id: 'YOUR_ACCESS_KEY_ID', aws_secret_access_key: 'YOUR_SECRET_ACCESS_KEY'}

