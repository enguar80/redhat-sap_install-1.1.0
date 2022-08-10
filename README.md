Red Hat Enterprise Linux System Roles for SAP Ansible Collection
=====================================

Red Hat Enterprise Linux System Roles for SAP is a set of roles for preparing Red Hat Enterprise Linux systems for the initial installation of SAP NetWeaver and SAP HANA, for installing SAP HANA Scale-Up and Scale-Out, and for installing a SAP HANA Two-Node Scale-Up cluster.

## Dependencies

If installing from RPM, any dependencies will be installed with the package.
Otherwise, the dependencies are listed in `requirements.txt` and/or `bindep.txt`.

## Installation

There are currently two ways to use the Red Hat Enterprise Linux System Roles for SAP Collection in your setup.

### Installation from Automation Hub

You can install the collection from Automation Hub by running:
```
ansible-galaxy collection install redhat.sap_install
```

After the installation, the roles are available as `redhat.sap_install.<role_name>`.

Please see the [Using Ansible collections documentation](https://docs.ansible.com/ansible/devel/user_guide/collections_using.html) for further details.

### Installation via RPM

You can install the collection with the software package management tool `dnf` by running:
```
dnf install rhel-system-roles-sap
```

## Documentation
The official RHEL System Roles for SAP documentation can be found [here](https://access.redhat.com/articles/4488731).

## Support

### Supported Ansible Versions

The supported Ansible versions are aligned with currently maintained Ansible versions that support Collections (Ansible 2.9 and later). You can find the list of maintained Ansible versions [here](https://docs.ansible.com/ansible/latest/reference_appendices/release_and_maintenance.html#release-status).

### Modules and Plugins

The modules and other plugins in this collection are private, used only internally to the collection, unless otherwise noted.

### Fully Supported Roles

<!--ts-->
  * sap_general_preconfigure
  * sap_hana_preconfigure
  * sap_netweaver_preconfigure
<!--te-->


### Roles in Technology Preview Support

<!--ts-->
  * sap_hana_install
  * sap_ha_install_hana_hsr
  * sap_ha_prepare_pacemaker
  * sap_ha_install_pacemaker
  * sap_ha_set_hana
<!--te-->
