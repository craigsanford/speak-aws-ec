Role Name
=========

A brief description of the role goes here.
This role will deploy a Silver Peak EdgeConnect Virtual into AWS.   



Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
- boto 
- bot3 botocore
- Reachable Silver Peak Orchestrator
  - template with known username and password configured 

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


AWS Access Key and Secret Key
region - AWS region to deploy to 
instance_type - What size AWS instance to use (default m4.xlarge)
 
 
Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost 
      roles:
         - role: aws_ec 
           vars: 
             region: us-west-1
             prefix: 172.20.65
License
-------

BSD

Author Information
------------------
Created by Craig Sanford (craigsanford@gmail.com)
