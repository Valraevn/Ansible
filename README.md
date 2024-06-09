# Ansible
This is a constantly changing set of ansible playbooks and dependant files. As is very much apparent I prefere having tasks in seperate files and running them together with the runner.yml playbook.
The current setup consists of a small cluster of VMs, 2 Pop!_OS, three Ubuntu and two Rocky.

If ran without a defined user in ansible.cfg, use --ask-become-pass. To limit a playbook use -l/--limit <host>, <group>.

For example a typical fresh setup would merit a run of update.yml + create_user.yml + install_packages.yml.



To do: \n Look into setting up roles, \n setup host variables
