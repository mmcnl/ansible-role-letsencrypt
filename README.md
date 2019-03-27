## Example Playbook

    - hosts: all
      tasks:
        - import_role:
            name: mmcnl.letsencrypt
          vars:
            letsencrypt_admin_email: admin@example.com
            letsencrypt_domains: 
              - example.com
              - dev.exmample.com

## License

MIT

