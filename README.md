tools
=================

setup tool

OS Platform
-----------------

### Debian

- trixie
- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `install_tools`

インストールするツール

#### `d2_version`

インストールするd2のバージョン

#### `tldr_version`

インストールするtldrのバージョン

#### `zns_version`

インストールするznsのバージョン

#### `bottom_version`

インストールするbottomのバージョン

#### `osv_scanner_version`

インストールするosv-scannerのバージョン

#### `tbls_version`

インストールするtblsのバージョン

#### `runn_version`

インストールするrunnのバージョン

#### `fd_version`

インストールするfdのバージョン

#### `bat_version`

インストールするbatのバージョン

#### `lazygit_version`

インストールするlazygitのバージョン

#### `lazydocker_version`

インストールするlazydockerのバージョン

#### `task_version`

インストールするtaskのバージョン

#### `delta_version`

インストールするdeltaのバージョン  
※この変数はDebian 12(Bookworm)以下の場合のみ評価されます

#### `duckdb_version`

インストールするDuckDBのバージョン

#### `assh_version`

インストールするasshのバージョン

#### `glow_version`

インストールするglowのバージョン

#### `pandoc_version`

インストールするpandocのバージョン

#### `drawio_version`

インストールするdraw.ioのバージョン

#### `gitleaks_version`

インストールするgitleaksのバージョン

#### `zx_latest_install`

zxを最新版に更新するか否か

#### `ni_latest_install`

niを最新版に更新するか否か

#### `mermaid_cli_latest_install`

mermaid-cliを最新版に更新するか否か

#### `codex_latest_install`

codexを最新版に更新するか否か

#### `goaccess_maxmind_account`

MaxMindのアカウントIDとライセンスキー  
@see https://dev.maxmind.com/geoip/geolite2-free-geolocation-data

#### `goaccess_maxmind_database_editions`

インストールするMaxMindのGeoIPデータベースのエディション

#### `goaccess_maxmind_database_path`

GoAccessに設定するGeoIPデータベースのパス

#### `goaccess_geoipupdate_interval`

GeoIPデータベースの自動更新頻度

#### `tesseract_ocr_languages`

Tesseract OCRの言語ファイル

#### `mecab_packages`

インストールするmecab関連のパッケージ

#### `mecab_extra_cfg`

mecabの設定

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `tools_dependency_packages`

#### `tools_add_repository_dependency_packages`

#### `tools_eza_apt_key_url`

#### `tools_eza_apt_key_download_dest`

#### `tools_eza_apt_key_dest`

#### `tools_goaccess_apt_key_url`

#### `tools_goaccess_apt_key_download_dest`

#### `tools_goaccess_apt_key_dest`

#### `tools_githubcli_apt_key_url`

#### `tools_githubcli_apt_key_download_dest`

#### `tools_githubcli_apt_key_dest`

#### `tools_tesseract_ocr_apt_key_url`

#### `tools_tesseract_ocr_apt_key_download_dest`

#### `tools_tesseract_ocr_apt_key_dest`

#### `tools_tbls_repo`

#### `tools_runn_repo`

#### `tools_osv_scanner_repo`

#### `tools_jc_repo`

#### `tools_fd_repo`

#### `tools_bat_repo`

#### `tools_rclone_repo`

#### `tools_restic_repo`

#### `tools_tldr_repo`

#### `tools_assh_repo`

#### `tools_zns_repo`

#### `tools_task_repo`

#### `tools_lazygit_repo`

#### `tools_lazydocker_repo`

#### `tools_delta_repo`

#### `tools_duckdb_repo`

#### `tools_pict_repo`

#### `tools_d2_repo`

#### `tools_glow_repo`

#### `tools_pandoc_repo`

#### `tools_drawio_repo`

#### `tools_gitleaks_repo`

#### `tools_diff_pdf_repo`

#### `tools_bottom_repo`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: tools
```

License
--------------

Apache License 2.0
