# LightEdge
Sample Ansible playbook for LightEdge

There are multiple Linux systems that need to be configured in a single Ansible playbook. One group containing 3 servers is located in the Texas site. Another group of 3 servers is located in the North Carolina site. The servers in North Carolina are running Redhat Enterprise Linux 8 and the Texas servers are running Ubuntu 20.04. All servers are reachable by the Ansible server. 

This playbook assumes these are fresh servers

Files:

AnsibleScenerio.txt - Scenerio provided by LightEdge

configure.yaml - the main playbook 

inventory - Updated inventory from AnsibleScenerio.txt

ntp.j2 - Modified ntp.conf file that will be updated depending on the server group
