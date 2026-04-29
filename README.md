# elk-9.1.1-playbook
This ansible playbook, is written for install Elastic Stack 9.1.1 without SSL and cluster. using private nexus registry.
Please set your variables in your environment. 
This playbook can set password for listed users: 
- elastic
- kibana_system
- logstash_system

I will develop this playbook for SSL and clustering settings. 
Be aware that I wrote this playbook for this environment:
- OS: Ubuntu 24.04 (noble)
- Existing Nexus Private registry
- Existing DEB files of ELK Stack on HOSTED REPOSITORY

Cause of the war at my country (IRAN vs USA and Israeil) for more than 40 DAYS, We didnt have access to internet. So I remove default linux repository from my  Ubuntu server, so that I havnt no errors for forign repositories.
