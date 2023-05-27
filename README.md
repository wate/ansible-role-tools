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

### `tesseract_ocr_langages`

Tesseract OCRの言語ファイル

### `d2_version`

インストールするd2のバージョン

### `osv_scanner_version`

インストールするosv-scannerのバージョン

### `tbls_version`

インストールするtblsのバージョン

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
