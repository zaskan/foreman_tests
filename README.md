# foreman_tests example output

    1.803 INFO     Updating inventory 4: Satellite
    1.830 DEBUG    Using base command: python /usr/bin/ansible-inventory -i /tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9/foreman.yml --playbook-dir /tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9 -vvvvv
    1.830 INFO     Reading Ansible inventory source: /tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9/foreman.yml
    1.832 INFO     Using VIRTUAL_ENV: /var/lib/awx/venv/ansible
    1.832 INFO     Using PATH: /var/lib/awx/venv/ansible/bin:/var/lib/awx/venv/awx/bin:/var/lib/awx/venv/awx/bin:/var/lib/awx/venv/awx/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin
    1.832 INFO     Using PYTHONPATH: /var/lib/awx/venv/ansible/lib/python3.6/site-packages:
    1.833 DEBUG    Using private credential data in '/tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9'.
    1.834 DEBUG    Using fresh temporary directory '/tmp/awx_proot_zh1r3hkd' for isolation.
    1.834 DEBUG    Running from `/tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9` working directory.
    3.894 ERROR    ansible-inventory 2.9.20
    3.894 ERROR      config file = /etc/ansible/ansible.cfg
    3.894 ERROR      configured module search path = ['/var/lib/awx/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
    3.894 ERROR      ansible python module location = /usr/lib/python3.6/site-packages/ansible
    3.894 ERROR      executable location = /usr/bin/ansible-inventory
    3.894 ERROR      python version = 3.6.8 (default, Mar 18 2021, 08:58:41) [GCC 8.4.1 20200928 (Red Hat 8.4.1-1)]
    3.895 ERROR    Using /etc/ansible/ansible.cfg as config file
    3.895 ERROR    setting up inventory plugins
    3.895 ERROR    /var/lib/awx/venv/ansible/lib/python3.6/site-packages/urllib3/connectionpool.py:1004: InsecureRequestWarning: Unverified HTTPS request is being made. Adding certificate verification is strongly advised. See: https://urllib3.readthedocs.io/en/latest/advanced-usage.html#ssl-warnings
    3.895 ERROR      InsecureRequestWarning,
    3.895 ERROR    {'total': 902, 'subtotal': 1, 'page': 1, 'per_page': 60, 'search': 'jsenkyri-puppeteer4.sysmgmt.lan', 'sort': {'by': None, 'order': None}, 'results': [{'ip': '192.168.140.40', 'ip6': '', 'environment_id': 4, 'environment_name': 'KT_Default_Organization_Library_jsenkyri_puppet_37', 'last_report': '2020-10-09 14:17:46 UTC', 'mac': '52:54:00:00:4a:16', 'realm_id': None, 'realm_name': None, 'sp_mac': None, 'sp_ip': None, 'sp_name': None, 'domain_id': 1, 'domain_name': 'sysmgmt.lan', 'architecture_id': 1, 'architecture_name': 'x86_64', 'operatingsystem_id': 17, 'operatingsystem_name': 'RHEL Server 7.8', 'subnet_id': 1, 'subnet_name': '192.168.140.0/24', 'subnet6_id': None, 'subnet6_name': None, 'sp_subnet_id': None, 'ptable_id': 99, 'ptable_name': 'Kickstart default', 'medium_id': None, 'medium_name': None, 'pxe_loader': 'PXELinux BIOS', 'build': False, 'comment': '', 'disk': '', 'installed_at': '2020-10-07 11:12:11 UTC', 'model_id': 1, 'hostgroup_id': 18, 'owner_id': 4, 'owner_name': 'Admin User', 'owner_type': 'User', 'enabled': True, 'managed': True, 'use_image': None, 'image_file': '', 'uuid': '12cd067c-2aa3-40aa-bcca-05b1b5933936', 'compute_resource_id': 1, 'compute_resource_name': 'satotest', 'compute_profile_id': 1, 'compute_profile_name': '1-Small', 'capabilities': ['build', 'image', 'new_volume'], 'provision_method': 'build', 'certname': 'jsenkyri-puppeteer4.sysmgmt.lan', 'image_id': None, 'image_name': None, 'created_at': '2020-10-07 10:54:47 UTC', 'updated_at': '2020-10-09 14:17:53 UTC', 'last_compile': '2020-10-09 11:25:22 UTC', 'global_status': 2, 'global_status_label': 'Error', 'uptime_seconds': 25318936, 'organization_id': 1, 'organization_name': 'Default Organization', 'location_id': 2, 'location_name': 'Default Location', 'puppet_status': 0, 'model_name': 'KVM', 'configuration_status': 0, 'configuration_status_label': 'No reports', 'build_status': 0, 'build_status_label': 'Installed', 'errata_status': 3, 'errata_status_label': 'Security errata applicable', 'subscription_status': 5, 'subscription_status_label': 'Simple Content Access', 'purpose_sla_status': 0, 'purpose_sla_status_label': 'Unknown', 'purpose_role_status': 0, 'purpose_role_status_label': 'Unknown', 'purpose_usage_status': 0, 'purpose_usage_status_label': 'Unknown', 'purpose_addons_status': 0, 'purpose_addons_status_label': 'Unknown', 'purpose_status': 0, 'purpose_status_label': 'Unknown', 'name': 'jsenkyri-puppeteer4.sysmgmt.lan', 'id': 2892, 'puppet_proxy_id': 1, 'puppet_proxy_name': 'ktordeur-sat65.sysmgmt.lan', 'puppet_ca_proxy_id': 1, 'puppet_ca_proxy_name': 'ktordeur-sat65.sysmgmt.lan', 'openscap_proxy_id': 1, 'openscap_proxy_name': 'ktordeur-sat65.sysmgmt.lan', 'puppet_proxy': {'name': 'ktordeur-sat65.sysmgmt.lan', 'id': 1, 'url': 'https://ktordeur-sat65.sysmgmt.lan:9090'}, 'puppet_ca_proxy': {'name': 'ktordeur-sat65.sysmgmt.lan', 'id': 1, 'url': 'https://ktordeur-sat65.sysmgmt.lan:9090'}, 'openscap_proxy': {'name': 'ktordeur-sat65.sysmgmt.lan', 'id': 1, 'url': 'https://ktordeur-sat65.sysmgmt.lan:9090'}, 'hostgroup_name': 'jsenkyri-puppet', 'hostgroup_title': 'jsenkyri-puppet', 'content_facet_attributes': {'id': 188, 'uuid': '2bed32f2-a8b2-4fed-8eff-1acb63773f6f', 'content_view_id': 37, 'content_view_name': 'jsenkyri-puppet', 'lifecycle_environment_id': 1, 'lifecycle_environment_name': 'Library', 'content_source_id': 1, 'content_source_name': 'ktordeur-sat65.sysmgmt.lan', 'kickstart_repository_id': None, 'kickstart_repository_name': None, 'errata_counts': {'security': 0, 'bugfix': 0, 'enhancement': 0, 'total': 0}, 'applicable_package_count': 299, 'upgradable_package_count': 0, 'applicable_module_stream_count': 0, 'upgradable_module_stream_count': 0, 'content_view': {'id': 37, 'name': 'jsenkyri-puppet'}, 'lifecycle_environment': {'id': 1, 'name': 'Library'}, 'content_source': {'id': 1, 'name': 'ktordeur-sat65.sysmgmt.lan', 'url': 'https://ktordeur-sat65.sysmgmt.lan:9090'}, 'kickstart_repository': None}, 'subscription_global_status': 0, 'subscription_facet_attributes': {'id': 2338, 'uuid': '2bed32f2-a8b2-4fed-8eff-1acb63773f6f', 'last_checkin': '2020-10-20 11:25:32 UTC', 'service_level': '', 'release_version': None, 'autoheal': True, 'registered_at': '2020-10-07 11:04:40 UTC', 'registered_through': 'ktordeur-sat65.sysmgmt.lan', 'purpose_role': '', 'purpose_usage': '', 'hypervisor': False, 'user': None, 'purpose_addons': []}}]}
    3.895 ERROR    ('jsenkyri-puppeteer4.sysmgmt.lan', 2892)
    3.895 ERROR    Parsed /tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9/foreman.yml inventory source with auto plugin
    3.895 DEBUG    Finished loading from source: /tmp/bwrap_181_ax4ymsy3/awx_181_ds05bxf9/foreman.yml
    3.895 INFO     Processing JSON output...
    3.895 DEBUG    Loaded group: all
    3.895 DEBUG    Loaded group: foreman_jsenkyri_puppet
    3.895 DEBUG    Adding child group foreman_jsenkyri_puppet to parent all
    3.895 DEBUG    Loaded host: jsenkyri-puppeteer4.sysmgmt.lan
    3.895 DEBUG    Adding host jsenkyri-puppeteer4.sysmgmt.lan to group foreman_jsenkyri_puppet
    3.895 DEBUG    Adding child group foreman_jsenkyri_puppet to parent all
    3.896 INFO     Loaded 1 groups, 1 hosts
    3.967 DEBUG    Inventory variables unmodified
    3.970 DEBUG    Group "foreman_jsenkyri_puppet" variables unmodified
    3.983 DEBUG    Host "jsenkyri-puppeteer4.sysmgmt.lan" variables updated
    3.996 DEBUG    Host "jsenkyri-puppeteer4.sysmgmt.lan" already in group "foreman_jsenkyri_puppet"
    4.030 INFO     Inventory import completed for Sat in 2.2s
