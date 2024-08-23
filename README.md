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

### `fd_version`

インストールするfdのバージョン

### `bat_version`

インストールするbatのバージョン

### `lazygit_version`

インストールするlazygitのバージョン

### `delta_version`

インストールするdeltaのバージョン

### `glow_version`

インストールするglowのバージョン

### `pandoc_version`

インストールするpandocのバージョン

### `hugo_version`

インストールするHugoのバージョン

### `hugo_extended`

インストールするHugoのタイプ

### `goaccess_maxmind_account`

MaxMindのアカウントIDとライセンスキー  
@see https://dev.maxmind.com/geoip/geolite2-free-geolocation-data

### `goaccess_maxmind_database_editions`

インストールするMaxMindのGeoIPデータベースのエディション

### `goaccess_maxmind_database_path`

GoAccessに設定するGeoIPデータベースのパス

### `goaccess_geoipupdate_interval`

GeoIPデータベースの自動更新頻度

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
