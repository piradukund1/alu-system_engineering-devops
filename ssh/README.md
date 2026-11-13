# SSH

Project files for connecting to a remote Ubuntu server with SSH key pairs.

| File | Description |
|------|-------------|
| `0-use_a_private_key` | Connects to the server as `ubuntu` using the private key `~/.ssh/school` |
| `1-create_ssh_key_pair` | Creates a 4096-bit RSA key pair named `school`, protected by the passphrase `betty` |
| `2-ssh_config` | SSH client config that uses `~/.ssh/school` and refuses password authentication |
