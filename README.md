# Project1-Ansible-Deploy_NewNetwork-SecPol

Goal:  With Ansible, create new network interfaces with ip addresses pre-determined, leverage Jinja2 templating as much as possible, provide basic network security to the new network.    

Playbook Described:  This playbooks intention is to create a new network and network interfaces on the respective devices. The network will be predetermined and allocated based on the Neverland Network structure. This playbook will also deploy various network access control lists and Palo Alto security policies to provide a layer of industry standard security.  The playbook will also provide levels of pre deployment checks and post deployment verifications through the use of display within the ansible deployment tool, basically print to screen.
