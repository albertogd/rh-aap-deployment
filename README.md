# rh-aap-deployment
Red Hat Ansible Automation Platform 2.1 deployment 

## Usage
Parameters required:

### Installation:
    aap_installation_url: Ansible Automation Platform 2.1.1 Setup Bundle URL with user and auth parameters

###  Automation Controllers:
    aap_automation_controllers: List of automation controller hosts
    aap_vg_name: Name of the VG (by default vg_root)
    aap_lv_name: Name of the LV where var is located (by default var)

###  Execution Nodes:
    aap_execution_nodes: List of execution nodes

###  Hop Nodes:
    aap_hop_nodes
  
###  Postgresql:
    aap_pg_database: PostgreSQL database name
    aap_pg_username: PostgreSQL username
    aap_pg_password: PostreSQL Password
    aap_pg_host: PostgreSQL host
    aap_pg_port: PostgreSQL Port (be default )

###  Red Hat Registry:
    aap_registry_username
    aap_registry_password

###  Controller Certificates:
    aap_controller_cert_path: path to the Controller app certificate
    aap_controller_cert_path: path to the Controller app key certificate
