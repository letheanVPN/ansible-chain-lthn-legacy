Role Name
=========

Role Variables
--------------

- lethean_rpc_bind_ip: "{{ ansible_default_ipv4.address|default(ansible_all_ipv4_addresses[0]) }}"
- lethean_p2p_bind_ip: "{{ ansible_default_ipv4.address|default(ansible_all_ipv4_addresses[0]) }}"
- lethean_rpc_bind_port: 48782
- lethean_p2p_bind_port: 48772
- lethean_data_dir: /var/lib/lthn-legacy-chain
- lethean_log_file: /var/log/lthn-legacy-chain.log
- lethean_log_level: 0


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: chain_lthn_legacy}

License
-------

EUPL-1.2
