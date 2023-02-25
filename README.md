minio
=================

Setup MinIO

OS Platform
-----------------

### Debian

- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `minio_version`

MinIOのバージョン

### `minio_address_host`

アドレス(ホスト)

### `minio_address_port`

アドレス(ポート)

### `minio_console_address_host`

コンソールアドレス(ホスト)

### `minio_console_address_port`

コンソールアドレス(ポート)

### `minio_volumes`

データの保存先

### `minio_root_user`

管理ユーザー名

### `minio_root_password`

管理ユーザーパスワード

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: minio
```

License
--------------

Apache License 2.0
