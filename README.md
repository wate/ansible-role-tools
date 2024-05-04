tool
=================

setup tool

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `install_tools`

インストールするツール

### `d2_version`

インストールするd2のバージョン

### `osv_scanner_version`

インストールするosv-scannerのバージョン

### `tbls_version`

インストールするtblsのバージョン

### `runn_version`

インストールするrunnのバージョン

### `delta_version`

インストールするdeltaのバージョン

### `glow_version`

インストールするglowのバージョン

### `pandoc_version`

インストールするpandocのバージョン

### `hugo_version`

インストールするHugoのバージョン

### `hugo_install_type`

インストールするHugoのタイプ

### `tesseract_ocr_langages`

Tesseract OCRの言語ファイル

### `mecab_packages`

インストールするmecab関連のパッケージ

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
