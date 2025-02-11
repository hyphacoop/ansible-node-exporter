# ansible-node-exporter

`node_exporter_version` 
- **Description:** Version of node-exporter to be installed
- **Default:** `1.3.1`

`node_exporter_listen_localhost`
- **Description:** have node exporter listen on localhost only
- **Default:** `false`

## Example

`requirements.yml`
```
---
roles:
- name: node-exporter
  src: https://github.com/hyphacoop/ansible-node-exporter.git
  version: main
```

Install
```
ansible-galaxy install -r requirements.yml
```
