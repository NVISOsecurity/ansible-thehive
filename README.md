# ansible-thehive
Ansible role for installing and configuring [TheHive](https://github.com/TheHive-Project/TheHive) and [Cortex](https://github.com/TheHive-Project/Cortex).

Optionally this role can install [thehive-sentinel-hooks](https://github.com/NVISO-BE/thehive-sentinel-integration) to integrate TheHive with Azure Sentinel and [thehive-sentinel-incidents](https://github.com/NVISO-BE/thehive-sentinel-integration) to pull Azure Sentinel incidents to TheHive.

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install TheHive
  import_role:
    name: ansible-thehive
```

## License

ansible-thehive is released under the GNU GENERAL PUBLIC LICENSE v3 [GPL-3.0](LICENSE).