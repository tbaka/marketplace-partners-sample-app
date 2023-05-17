# Wordpress Marketplace App Reference Diagram

The following reference diagram illustrates variable handling and task flow in the Ansible playbooks to facilate end-user deployments with LAMP or LEMP web stacks, and one of three DNS configurations with CertBot SSL. 

Additional design considerations are the safe handling of UDF variables, which are isolated to a unique tty and inaccessiable via terminal after the inital deployment, and utilization of linode_helper roles to reduce unique tasks across multiple deployments. 
 
![Diagram illustrating variable handling in Wordpress Marketplace App](./wordpress_oca_vars.svg)
<img src="./wordpress_oca_vars.svg">