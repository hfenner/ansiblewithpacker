# Advanced Ansible: Inventories and Lookups and Jinja2, Oh My! (with a side of Packer)
### Workshop at SecureWV 2020
### https://www.securewv.org/schedule-2020/
### Saturday November 7th, 2020 (9AM-12PM EST)

### Slides Here: https://docs.google.com/presentation/d/1NLRR-qgmF-tSI44p4tuWSHZ5h6rffUR84Nh9faL82fc/edit?usp=sharing

## Abstract
If you're reaching for an Ansible module to get information for your playbook, you're probably doing it wrong. If you find yourself wishing for nested loops on tasks to extract variables, you're probably doing it wrong. If you are creating static inventory files to list your hosts, you might be doing it right. Unless you're not using those inventory files to create the hosts you're listing. Because then you're probably doing it wrong.  It's okay to use Ansible in a way that works for you. However, there are a lot of powerful options that can make your code more maintainable, easier to collaborate on, and faster to write. Come learn about how to leverage dynamic inventories to get automated host listing, lookups to pull in real-time data, and Jinja2 filters to pare that huge list of facts down to a the list of IP addresses you actually need. We'll be using an Ansible to create and deploy a Packer configuration file that builds several VM's including a CentOS and Vyos system.

## vSphere Login Info for infrabuild.xyz
Username: administrator@vsphere.infrabuild.xyz
Password: BadPassword1234$
Host: https://vsphere.infrabuild.xyz

## vSphere Login Info for disconnect.blue
Username: administrator@vsphere.disconnect.blue
Password: BadPassword1234$
Host: https://vsphere.disconnect.blue

##
[Exercise 1: Build your first system with Packer](1_first_system)


## References
#### Ansible Inventory for Fun and Profit
How to combine and flexibly employ Ansible inventories
https://www.ansible.com/ansible-inventory-for-fun-and-profit



#### How to use multiple files in a roles defaults folder
https://stackoverflow.com/questions/51818264/how-to-split-an-ansible-roles-defaults-main-yml-file-into-multiple-files

#### How to use Advanced Terraform loops and filters
https://alexharv074.github.io/2019/06/02/adventures-in-the-terraform-dsl-part-iii-iteration-enhancements-in-terraform-0.12.html#for_each-expressions

#### Comprehensive Terraform Guide from Gruntworks
https://blog.gruntwork.io/a-comprehensive-guide-to-terraform-b3d32832baca
