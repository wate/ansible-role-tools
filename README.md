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

### `mailpit_version`

インストールするmailpitのバージョン

### `mailpit_cfg`

mailpitの設定

### `msmtp_default_cfg`

msmtpの設定(defaults)

### `msmtp_acounts`

msmtpの設定(acount)

### `msmtp_account_default`

msmtpの設定(デフォルトで理容するアカウント)

### `msmtpd_cfg`

msmtpdの設定(/etc/default/msmtpd)

### `d2_version`

インストールするd2のバージョン

### `osv_scanner_version`

インストールするosv-scannerのバージョン

### `tbls_version`

インストールするtblsのバージョン

### `mailhog_version`

インストールするmailhog(本体)のバージョン

### `mailhog_mhsendmail_version`

インストールするmailhog(mhsendmail)のバージョン

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
