tool
=================

setup tool

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

### `install_tools`

インストールするツール

### `tbls_version`

tblsのバージョン

### `mailhog_version`

mailhog(本体)のバージョン

### `mailhog_mhsendmail_version`

mailhog(mhsendmail)のバージョン

### `mailhog_cfg`

mailhogの設定

### `mecab_extra_cfg`

mecabの設定

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: tool
```

License
--------------

Apache License 2.0
