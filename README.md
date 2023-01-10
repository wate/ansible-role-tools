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

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `install_tools`

インストールするツール

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
