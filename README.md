A repository of various Ansible Playbooks

Usage:
  ansible-playbook -l <host> -u root -i host site.yml -t <tags>

Hosts:
  development

Tags:
  bootstrap:
    Install required Python packages on host to use Ansible Playbooks

  common: apt,locale,ntp,ssh
    Common system configuration to setup a host
    Sub-tags can be specified instead of 'common'
