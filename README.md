minio
=================

Setup MinIO

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `minio_version`

MinIOのバージョン

#### `minio_address_host`

アドレス(ホスト)

#### `minio_address_port`

アドレス(ポート)

#### `minio_console_address_host`

コンソールアドレス(ホスト)

#### `minio_console_address_port`

コンソールアドレス(ポート)

#### `minio_volumes`

データの保存先

#### `minio_root_user`

管理ユーザー名

#### `minio_root_password`

管理ユーザーパスワード

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `minio_user`

#### `mini_group`

#### `minio_environment_file`

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
